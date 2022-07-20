<template>
    <li :key="list">{{list}}</li>
</template>

<script>
export default {
  props: {
    list: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    li {
        list-style: none;
        padding: 12px 20px;
        color: #fff;
    }
</style>