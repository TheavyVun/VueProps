<template>
    <form action="">
        <h2>Login</h2>
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
    form {
        padding: 20px;
        border-radius: 10px;
        box-shadow: rgba(0, 0, 0, 0.19) 0px 10px 20px, rgba(0, 0, 0, 0.23) 0px 6px 6px;
        background-image: linear-gradient(to right, #ff8177 0%, #ff867a 0%, #ff8c7f 21%, #f99185 52%, #cf556c 78%, #b12a5b 100%);
    }
    form:hover {
        background-image: linear-gradient(to left, #ff8177 0%, #ff867a 0%, #ff8c7f 21%, #f99185 52%, #cf556c 78%, #b12a5b 100%);
    }
    h2 {
        color: #fff;
        text-align: center;
        margin: 0;
        margin-bottom: 14px;
    }
    .btn {
        background-image: linear-gradient(to left, #30cfd0 0%, #330867 100%);
    }
    .btn:hover {
        background-image: linear-gradient(to right, #30cfd0 0%, #330867 100%);
    }
</style>