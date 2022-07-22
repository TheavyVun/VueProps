<template>
    <footer>
        <footer-left />
        <footer-right />
    </footer>
</template>

<script>
import FooterLeft from './FooterLeft.vue'
import FooterRight from './FooterRight.vue'
export default {
    components: {
        "footer-left": FooterLeft,
        "footer-right": FooterRight,
    },

}
</script>

<style>
    footer {
        display: flex;
        color: #fff;
        text-align: center;
        background-image: linear-gradient(to right, #ff8177 0%, #ff867a 0%, #ff8c7f 21%, #f99185 52%, #cf556c 78%, #b12a5b 100%);

    }
    
</style>