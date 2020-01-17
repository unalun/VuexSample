<template>
  <div id="app">
    <Counter/>
    <DecreaseCounter />
  </div>
</template>

<script>
import Counter from './components/Counter'
import DecreaseCounter from './components/DecreaseCounter'
export default {
  name: 'app',
  components: {
    Counter,
    DecreaseCounter
  }
}
</script>

<style>

</style>
