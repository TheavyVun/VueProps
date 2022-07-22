<template>
    <button class="btn">{{namebtn}}</button>
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
        color: #fff;
    }
    .btn:hover {
      cursor: pointer;
    }
</style>