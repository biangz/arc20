<template>
    <header class="sticky bg-black z-[99] top-0 w-full flex items-center px-[0.8rem] md:px-[5.12rem]">
        <Logo class="logo block w-[2rem]"/>
        <!-- <div class="flex items-center gap-x-4 ml-auto">
            <w3m-button :balance="'hide'"/>
        </div> -->
        <a-button @click="handleNotification" class="ml-auto" type="primary" shape="round">Coming Soon..</a-button>
    </header>
</template>

<script setup>
import { onMounted } from 'vue';
import { getAccount } from '@wagmi/core';
// import { useWeb3Modal } from '@web3modal/wagmi/vue'
// const { open, close } = useWeb3Modal()
import { Notification } from '@arco-design/web-vue';

import { useAuthStore } from '@/store/auth'
const authStore = useAuthStore()

const handleIncrece = (address) => {
    authStore.setAddress(address)
}

const handleConnectWallet = async () => {
    open().then(res => {
        console.log('res:', res)
    })
    
}

const handleNotification = () => {
    Notification.info({
        title: 'Coming soon!',
    })
}

onMounted(() => {
})

</script>

<style scoped lang="less">
header {
    box-sizing: border-box;
    height: var(--header-height);
    border: 1px solid rgba(0,0,0,0.1);
}
</style>