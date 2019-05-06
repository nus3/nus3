<template>
    <main class="container">
        <h1 class="title">hello</h1>
    </main>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
})
</script>

<style lang="scss" scoped>
$bgColor: #364046;
$textColor: #e3f2fd;

.container {
    width: 100vw;
    height: 100vh;
    background-color: $bgColor;

    .title {
        margin: 0;
        color: $textColor;
        font-size: 50px;
        margin-bottom: 20px;
    }
}
</style>
