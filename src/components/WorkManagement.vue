<script setup lang="ts">

    import imgContainer2 from '../assets/img/Image-container2.svg'
    import { ChevronDown, ChevronDownCircle, ArrowRight } from 'lucide-vue-next';
    import imgWorkTogether from '../assets/img/Work Together Image.svg'

</script> 

<template>

    <section class="secWorkManagement">

        <div class="projectManagement">
            <div>
                <div class="WorkManContent">
                    <h2>Project Management</h2>
                    <p>
                        Images, videos, PDFs and audio files are supported. Create math expressions and diagrams directly from the app. Take photos with the mobile app and save them to a note.
                    </p>
                </div>
                <button class="getStartedBtn">
                    Get Started
                    <ArrowRight />
                </button>
            </div>
            <div>
                <img :src="imgContainer2" alt="">
            </div>
        </div>
            
        <div class="projectManagement">
            <div>
                <img :src="imgWorkTogether" alt="">
            </div>
            <div>
                <div class="WorkManContent">
                    <h2>Work together</h2>
                    <p>
                        With whitepace, share your notes with your colleagues and collaborate on them.
                        You can also publish a note to the internet and share the URL with others.
                    </p>
                </div>
                <button class="getStartedBtn">
                    Try it Now
                    <ArrowRight />
                </button>
            </div>
        </div>

    </section>

</template>

<style scoped>

    .secWorkManagement {
        display: flex;
        flex-direction: column;
        padding: 8.7em 13.7em;
        gap: 6.2em;
    }

    .projectManagement {
        display: flex;
        align-items: center;
        gap: 3.7em;
    }

    .WorkManContent {
        display: flex;
        flex-direction: column;
        gap: 1.5em ;
    }

    .WorkManContent h2 {
        font-size: 72px;
    }

    .WorkManContent p {
        font-size: 18px;
        padding-right: 1.3em;
    }

    .getStartedBtn {
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