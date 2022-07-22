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


}
</script>

<style>
    nav {
        background-image: linear-gradient(to right, #ff8177 0%, #ff867a 0%, #ff8c7f 21%, #f99185 52%, #cf556c 78%, #b12a5b 100%);
    }
    nav:hover {
        background-image: linear-gradient(to left, #ff8177 0%, #ff867a 0%, #ff8c7f 21%, #f99185 52%, #cf556c 78%, #b12a5b 100%);
    }
    ul {
        display: flex;
        margin: 0;
    }


</style>