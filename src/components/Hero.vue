<script setup lang="ts">
    import imgContainer from '../assets/img/image-container.png'
    import { ChevronDown, ChevronDownCircle, ArrowRight } from 'lucide-vue-next';

</script>

<template>

    <section class="secHero">
        <div class="HeroContainer">
            <div class="titleContent">
                <h1>
                    Get More Done with whitepace
                </h1>
                <p>
                    Project management software that enables your teams to collaborate, plan, analyze and manage everyday tasks
                </p>
            </div>
            <div class="ContainerButton">
                <button class="ButtonTry">
                    Try Whitepace free
                    <ArrowRight class="icon"/>
                </button>
            </div>
        </div>
        <div>
            <img :src="imgContainer" alt="">
        </div>
    </section>

</template>

<style scoped>

    .secHero {
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 8.7em 13.7em;
        background-color: #043873;
    }

    .titleContent {
        display: flex;
        flex-direction: column;
        gap: 1.5em;
        color: #ffff;
    }

    .titleContent h1 {
        font-size: 65px;
    }

    .titleContent p {
        font-size: 18px;
    }

    .HeroContainer {
        display: flex;
        flex-direction: column;
        gap: 3.7em;
    }

    .ButtonTry {
        display: flex;
        align-items: center;
        gap: 0.6em;
        padding: 1em 2.5em;
        border: none;
        border-radius: 8px;
        cursor: pointer;
        font-size: 16px;
        background-color: #4F9CF9;
        color: #ffff;
    }

</style>