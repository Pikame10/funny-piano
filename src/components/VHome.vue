<template>
    <div class="Home">

        <div class="Home__Title md:flex">
            <div class="Title">
                <img src="@/assets/svg/TheEmojiPiano.svg" alt="" class="title__icon">
            </div>
        </div>
        <v-piano></v-piano>
    </div>
</template>



<script>
    import VPiano from '@/components/VPiano'

    export default {
        components: {
            VPiano,
        }
    }

</script>

<style lang="postcss" scoped>
   
    .Home {
       
        content: '';
        display: block;
        height: 100%;
        width: 100%;
        background: linear-gradient(157deg, rgba(131, 58, 180, 1) 0%, rgba(253, 29, 29, 1) 50%, rgba(252, 176, 69, 1) 100%);
        position: absolute;
        top: 0;
        left: 0;
        z-index: -1;
    }

    @media only screen and (min-width: 1700px) and (max-width: 2500px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 790px;
            top: 40px;

        }
    }

    @media only screen and (min-width: 1500px) and (max-width: 1700px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 690px;
            top: 40px;

        }
    }

    @media only screen and (min-width: 1250px) and (max-width: 1500px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 590px;
            top: 40px;

        }
    }

    @media only screen and (min-width: 1000px) and (max-width: 1250px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 450px;
            top: 40px;

        }
    }

    
    @media only screen and (min-width: 850px) and (max-width: 1000px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 310px;
            top: 40px;

        }
    }

    @media only screen and (min-width: 750px) and (max-width: 850px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 250px;
            top: 40px;

        }
    }

    @media only screen and (min-width: 600px) and (max-width: 750px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 220px;
            top: 40px;

        }
    }

    @media only screen and (min-width: 500px) and (max-width: 600px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 150px;
            top: 40px;

        }
    }

    @media only screen and (min-width: 400px) and (max-width: 500px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 110px;
            top: 40px;

        }
    }

    @media only screen and (min-width: 200px) and (max-width: 399px) {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 75px;
            top: 40px;

        }
    }
</style>