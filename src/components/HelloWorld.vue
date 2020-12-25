<template>
<input/>
</template>

<script setup>
import {defineEmit,defineProps} from 'vue'
const props = defineProps(['yo'])
const emit = defineEmit(['emit'])
emit('yee', props.yo)
</script>

