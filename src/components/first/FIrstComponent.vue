<template>
    <div>
        {{ count }}
        <button @click="add">点我增加</button>
    </div>
</template>
<script setup lang="ts">
import { ref } from "vue";
const count = ref(0);
function add() {
    count.value++;
}
</script>
<style lang="css"></style>
