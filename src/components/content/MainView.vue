<template>
    <div class="main">
        <card-view />
        <card-view />
        <card-view />
    </div>
</template>

<script>
import Card from './CardView.vue'
export default {
    components: {
        "card-view": Card,
    },
    props: {
        // msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .main {
        width: 70%;
        padding: 30px;
        border-right: 1px dotted;
    }
</style>