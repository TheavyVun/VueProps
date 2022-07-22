<template>
    <input :type="typeinput" class="formcontrol" :placeholder="sms">
</template>

<script>
export default {
  props: {
    sms: String,
    typeinput: String
  }
}
</script>

<style>
    .formcontrol {
        width: 100%;
        padding: 10px 20px;
        box-sizing: border-box;
        margin-bottom: 10px;
    }
</style>