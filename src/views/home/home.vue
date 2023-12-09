<template>
    <router-view v-slot="{ Component, route }" :key="$route.fullPath">
        <!-- <Header></Header> -->
        <main>
            <keep-alive>
                <component :is="Component" />
            </keep-alive>
        </main>
        <!-- <Footer></Footer> -->
    </router-view>
</template>

<script setup>

</script>

<style scoped>
main {
    min-height: 100vh;
}
</style>