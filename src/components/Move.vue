<script setup>
import { useRouter } from "vue-router";
const router = useRouter();
const main = () => {
    router.push({
        path: "/",
    });
};
</script>
<template>
    <div class="board">
        <h1>Move Main</h1>
        <button @click="main()">Main</button>
    </div>
</template>
<style scoped>
.board {
    margin: 10% 30%;
}
</style>