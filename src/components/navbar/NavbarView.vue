<template>
    <nav>
        <ul>
            <list-view list="Home" />
            <list-view list="About Us" />
            <list-view list="Services" />
            <list-view list="Contact Us" />
        </ul>
    </nav>
</template>

<script>
import List from './ListView.vue'
export default {
    components: {
        "list-view": List,
    },
    props: {
    },

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    nav {
        background: rgb(195, 21, 21);
    }
    ul {
        display: flex;
        margin: 0;
    }


</style>