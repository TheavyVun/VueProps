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

<style>
    .btn {
        border: none;
        padding: 8px 20px;
        border-radius: 9px;
        background: rgb(194, 8, 8);
        color: #fff;
    }
</style>