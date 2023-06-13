<script lang="ts" setup>
import { ref } from 'vue';

const count = ref(0);

function increase() {
    count.value++;
}
</script>

<template>
    <div class="app">
        <div class="counter">
            <p>{{ count }}</p>
            <button @click="increase">+</button>
        </div>
    </div>
</template>

<style lang="css" scoped>
.app {
    width: 100vw;
    height: 100vh;

    .counter {
        width: 200px;
        margin: 60px auto;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
}
</style>
