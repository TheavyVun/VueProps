<template>
    <div class="main">
        <card-view v-for="post of posts" :key="post" :post="post" />

    </div>
</template>

<script>
import Card from './CardView.vue'
import axios from "axios"
export default {
    components: {
        "card-view": Card,
    },
    props: {
    },
    data() {
        return {
            posts: [],
        }
    },
    methods: {
        
    },
    mounted() {
        axios.get('http://127.0.0.1:81/api/posts').then(res=> {
        this.posts = res.data;
        })
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