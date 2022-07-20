<template>
    <button class="btn" :key="namebtn">{{namebtn}}</button>
</template>

<script>
export default {
  props: {
    namebtn: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .btn {
        border: none;
        padding: 8px 20px;
        border-radius: 9px;
        background: rgb(194, 8, 8);
        color: #fff;
    }
</style>