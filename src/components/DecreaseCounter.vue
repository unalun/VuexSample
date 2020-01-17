<template>
  <div>

    <button @click="decreaseCounter">decrease counter</button>
  </div>
</template>

<script>
  export default {
    methods: {
      decreaseCounter () {
        this.$store.dispatch('decreaseAction', 1)
      }
    },

    computed: {
      counter () {
        return this.$store.getters.counter
      }
    }
  }
</script>
