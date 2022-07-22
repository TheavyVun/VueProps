<template>
    <section>
        <div class="card" :key="post">
            <div class="card-title">
                <h3>{{post.title}}</h3>
            </div>
            <hr>
            <div class="card-body">
                <p>{{post.description}}</p>
                <button-view namebtn="Buy Now" />
            </div>
        </div>
    </section>
</template>

<script>
import Button from './ButtonView.vue'
export default {
    components: {
        "button-view": Button,
    },
    props: {
        post: Object,
    },

}
</script>

<style>
    .card {
        width: 100%;
        padding: 20px;
        border-radius: 8px;
        margin-bottom: 20px;
        border-top: 4px solid rgb(230, 23, 23);
        box-shadow: rgba(0, 0, 0, 0.19) 0px 10px 20px, rgba(0, 0, 0, 0.23) 0px 6px 6px;    
    }

    h3 {
        margin: 0;
    }
    .btn {
        background-image: linear-gradient(to right, #f83600 0%, #f9d423 100%);
    }
    .btn:hover {
        background-image: linear-gradient(to right, #f9d423 0%, #ff4e50 100%);
    }
</style>