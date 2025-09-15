<script setup lang="ts">

    import imgContainer2 from '../assets/img/Image-container2.svg'

</script> 

<template>

    <section class="secWorkManagement">

        <div>
            <div>
                <h1>Project Management</h1>
                <p>
                    Images, videos, PDFs and audio files are supported. Create math expressions and diagrams directly from the app. Take photos with the mobile app and save them to a note.
                </p>
            </div>
            <button>
                Get Started
            </button>
        </div>
        <div>
            <img :src="imgContainer2" alt="">
        </div>

    </section>

</template>

<style scoped>

    .secWorkManagement {
        display: flex;
        padding: 8.7em 13.7em;
    }

</style>