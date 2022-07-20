<template>
    <input type="text" class="formcontrol" :key="sms" :placeholder="sms">
</template>

<script>
export default {
  props: {
    sms: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .formcontrol {
        width: 100%;
        padding: 10px 20px;
        box-sizing: border-box;
        margin-bottom: 10px;
    }
</style>