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
        background: rgb(192, 34, 34);
        text-align: center;

    }
    
</style>