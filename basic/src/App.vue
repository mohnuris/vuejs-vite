<template>

  <div>{{ message }}</div>

  <input v-model="message"/>

<!--  2  way data binding-->
  <input :value="message" @input="message = $event.target.value">
</template>

<script>
export default {
data() {
  return {
    message: 'hi'
  }
}
}
</script>
