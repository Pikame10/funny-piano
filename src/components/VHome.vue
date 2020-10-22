<template>
    <div class="Home">

        <div class="Home__Title">
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
        background: linear-gradient(125deg, rgba(2, 0, 36, 1) 2%, rgba(28, 28, 105, 1) 88%, rgba(58, 222, 255, 1) 100%);
        position: absolute;
        top: 0;
        left: 0;
        z-index: -1;
    }

    @screen sm {
        .Home__Title .Title {

            position: absolute;
            width: 232px;
            height: 60px;
            left: 250px;
            top: 40px;

        }}

        @screen md {
            .Home__Title .Title {

                position: absolute;
                width: 232px;
                height: 60px;
                left: 300px;
                top: 40px;

            }
        }

        @screen lg {
            .Home__Title .Title {

                position: absolute;
                width: 232px;
                height: 60px;
                left: 300px;
                top: 40px;

            }
        }


        @screen xl {
            .Home__Title .Title {

                position: absolute;
                width: 232px;
                height: 60px;
                left: 800px;
                right: 1000px;
                top: 40px;

            }
        }
</style>