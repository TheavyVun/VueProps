<template>
    <form action="">
        <input-view typeinput="email" sms="email" />
        <input-view typeinput="password" sms="password" />
        <button-view  namebtn="Login" />
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

}
</script>

<style scoped>
    .btn {
        background: blue;
    }
</style>