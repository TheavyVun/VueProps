<template>
    <div class="side-bar">
        <form-view />
    </div>
</template>

<script>
import Form from './FormView.vue'
export default {
    components: {
        "form-view": Form,
    },

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    .side-bar {
        width: 30%;
        padding: 30px;
    }
</style>