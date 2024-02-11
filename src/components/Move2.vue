<script setup>
import { useRouter } from "vue-router";

const router = useRouter();
const move = () => {
    router.push({
        path: "/Move",
    });
};
</script>

<template>
    <div class="board">
        <h1>Move</h1>
        <button @click="move()">Move</button>
    </div>
</template>
<style scoped>
</style>