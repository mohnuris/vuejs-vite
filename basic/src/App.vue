<template>

<!--  <div>{{ message }}</div>-->

<!--  <input v-model="message"/>-->

<!--  2  way data binding-->
<!--  <input :value="message" @input="message = $event.target.value">-->

<!--  Conditional Rendering dengan v-if-->
  <div v-if="status">tampil</div>

  <button @click="setStatus">Toggle</button>
</template>

<script>
export default {
data() {
  return {
    // message: 'hi'
    status: false
  }
    },
  methods: {
    setStatus() {
      this.status = !this.status
  }
}
}
</script>
