<template>
    <section>
        <main-view />
        <sidebar-view />
    </section>
</template>

<script>
import Main from './MainView.vue'
import Sidebar from './SideBarView.vue'
export default {
    components: {
        "main-view": Main,
        "sidebar-view": Sidebar,
    },

}
</script>

<style>
    section {
        display: flex;
        box-sizing: border-box;
    }
</style>