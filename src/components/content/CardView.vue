<template>
    <section>
        <div class="card">
            <div class="card-title">
                <h3>Post 1</h3>
            </div>
            <hr>
            <div class="card-body">
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Repellat obcaecati vel sed adipisci facilis eligendi sequi, sint eos, iste, voluptatum cupiditate praesentium velit. Ut harum quis beatae aliquam, alias eligendi!</p>
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
        
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .card {
        padding: 20px;
        border-radius: 8px;
        margin-bottom: 20px;
        border-top: 4px solid rgb(230, 23, 23);
        box-shadow: rgba(0, 0, 0, 0.56) 0px 22px 70px 4px;
    }
    h3 {
        margin: 0;
    }
</style>