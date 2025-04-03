<script setup>
defineProps({
  msg: {
    type: String,
    required: false,
  },
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
    Hi Muna !
    </h3>
  </div>
</template>

<style scoped>

</style>
