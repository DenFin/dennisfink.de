<template>
    <component :is="type">{{  text }}</component>   
</template>

<script setup lang="ts">

defineProps<{
    text: String,
    type: String
}>()

</script>