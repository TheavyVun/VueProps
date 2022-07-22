<template>
    <div class="main">
        <card-view v-for="post of posts" :key="post" :post="post" />
    </div>
</template>

<script>
import Card from './CardView.vue'
export default {
    components: {
        "card-view": Card,
    },
    props: {
    },
    data() {
        return {
            posts: [
                {title: "Post 1", description: "Lorem ipsum dolor sit amet consectetue adipisicing elit. Magnam, nats."},
                {title: "Post 1", description: "Lorem ipsum dolor sit amet consectetue adipisicing elit. Magnam, nats."},
                {title: "Post 1", description: "Lorem ipsum dolor sit amet consectetue adipisicing elit. Magnam, nats."},
                {title: "Post 1", description: "Lorem ipsum dolor sit amet consectetue adipisicing elit. Magnam, nats."},
            ],
        }
    },

}
</script>

<style>
    .main {
        width: 70%;
        padding: 30px;
        border-right: 1px dotted;
        height: 80vh;
        overflow: auto;
    }
    .main::-webkit-scrollbar {
    display: none;
}
</style>