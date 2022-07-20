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
    props: {
        // msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    footer {
        display: flex;
        background: rgb(192, 34, 34);
        text-align: center;
    }
    
</style>