<template>

  <div>{{ count }}</div>
  
  <button @click="count++">Add 1</button>
</template>

<script>
export default {
data() {
  return {
    count: 0
  }
}
}
</script>
