<template>
    <form action="">
        <input-view sms="email" />
        <input-view sms="password" />
        <button-view namebtn="Login" />
    </form>
</template>

<script>
import Input from './InputView.vue';
import Button from './ButtonView.vue';
export default {
    components: {
        "input-view": Input,
        "button-view": Button,
    },
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .btn {
        background: blue;
    }
</style>