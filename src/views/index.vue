<template>
    <div class="main-container">
        <div class="flex w-full">
            <div class="top-left flex-1 flex items-center justify-center">
                <img class="block" src="../assets/images/icon-smile.png" alt="">
            </div>
            <div class="top-right"></div>
        </div>
        <div class="flex-1 title-box w-full flex flex-col items-start justify-center">
            <div class="flex items-center">
                <img class="w-[5rem] ml-4" src="../assets/images/logo.png" alt="">
                <div class="ml-2">
                    <img class="w-[20rem]" src="../assets/images/text-comingsooon.png" alt="">
                    <p><a class="underline font-weight text-white text-sm ml-1" href="https://lees-personal-organization.gitbook.io/ganc-the-best-btc-stable-coin-protocol/" target="_blank">Whitepaper</a></p>
                </div>
            </div>
        </div>
        <div class="footer w-full"></div>
    </div>
</template>

<script setup>
import { useAuthStore } from '@/store/auth'
import { ref, onMounted, reactive } from 'vue';
import { IconClose, IconArrowRight } from '@arco-design/web-vue/es/icon';
import AOS from "aos";

// onMounted
onMounted(() => {
    AOS.init();
})

</script>

<style scoped lang="less">
.main-container {
    height: 100vh;
    background: #1C1C1C;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    .top-left {
        background: url('../assets/images/bg-top-l.png') no-repeat center / cover;
        > img {
            width: 224px;
        }
    }
    .top-right {
        background: url('../assets/images/text-arc.png') no-repeat center / cover;
        width: 997px;
        height: 413px;
    }

    .title-box {
        background: url('../assets/images/bg-main.png') no-repeat left bottom / 70%, linear-gradient(to right, #1C1C1C 90%, #24BC7A 90%);
    }

    .footer {
        height: 66px;
        background: url('../assets/images/bg-footer.png') no-repeat center center / 100%;
    }
}
</style>