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

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    section {
        display: flex;
        box-sizing: border-box;
    }
</style>