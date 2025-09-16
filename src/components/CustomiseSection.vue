<script setup lang="ts">

    import imgContainer from '../assets/img/Illustration.svg'

</script>

<template>

    <section class="secUseExtention">
        <div class="useExtentionContainer">
            <div class="useExtention">
                <h2>
                    Use as Extension
                </h2>
                <p>
                    Use the web clipper extension, available on Chrome and Firefox, to save web pages or take screenshots as notes.
                </p>
            </div>
            <button class="goBtn">
                Let's Go
            </button>
        </div>
        <img :src="imgContainer" alt="">
    </section>

</template>

<style scoped>

    .secUseExtention {
        color: #ffff;
        background-color: #043873;
        display: flex;
        padding: 8.7em 13.7em;
        gap: 6.2em;
        align-items: center;
    }

    .useExtention h2 {
        font-size: 72px;
    }

    .useExtention p {
        font-size: 18px;
    }

    .goBtn {
        margin-top: 3.7em;
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