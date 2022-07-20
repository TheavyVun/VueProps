<template>
    <div class="footer-right">Footer Right</div>
</template>

<script>
export default {
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .footer-right {
        width: 100%;
        padding: 10px;
        border-left: 1px dotted;
    }
</style>