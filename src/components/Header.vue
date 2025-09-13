
<script setup lang="ts">
    import { ChevronDown, ChevronDownCircle, ArrowRight } from 'lucide-vue-next';
    import LogoWhiteSpace from '../assets/img/Logo.svg'
</script>

<template>

    <header class="header">
        <div class="headerContainer">
    
            <div class="ContainerLogo">
                <img :src="LogoWhiteSpace" alt="WhitespaceLogo">
            </div>
            <div class="ContainerSelections">

                <nav class="ContainerNav">
                    <ul>
                        <li>
                            <a href="#">
                                Products
                                <chevron-down class="icon" />
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Soluctions
                                <ChevronDown class="icon"/>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Resources
                                <ChevronDown class="icon"/>
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Pricing
                                <chevron-down class="icon"/>
                            </a>
                        </li>
                    </ul>
                </nav>
                
                <div class="ContainerButton">
                    <button class="loginButton">
                        Login
                    </button>
                    <button class="ctaButton">
                        Try Withpace Free
                        <ArrowRight class='icon' />
                    </button>
                </div>

            </div>

        </div>
    </header>

</template>

<style scoped>

    .header {
        background-color: #043873;
        padding: 1em 13.7em;
    }

    .headerContainer {
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 13.7em;
    }

    .ContainerSelections {
        display: flex;
        justify-content: space-between;
        align-items: center;
        gap: 3.7em;
    }

    .ContainerNav ul {
        display: flex;
        justify-content: space-between;
        gap: 1em;
        list-style: none;
        color: #ffff;
    }

    .ContainerNav a {
        display: flex;
        align-items: center;
        gap: 0.6em;
        opacity: 0.8;
        transition: opacity 0.2 ease-in-out;
        font-weight: 500;
        font-size: 16px;
    }

    .ContainerNav a:hover {
        opacity: 1;
    }

    .ContainerButton {
        display: flex;
        align-items: center;
        gap: 1em;
    }

    .loginButton,
    .ctaButton {
        padding: 1em 2.5em;
        border: none;
        border-radius: 8px;
        cursor: pointer;
        font-size: 16px;
    }

    .loginButton {
        background-color: #FFE492;
        color: #043873;
    }

    .ctaButton {
        display: flex;
        align-items: center;
        gap: 0.6em;
        background-color: #4F9CF9;
        color: #ffff;
    }

</style>
