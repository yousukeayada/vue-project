<template>
  <div>
    <MyHeader class=""></MyHeader>
    <MyBody></MyBody>
    <MyBody></MyBody>
    <MyBody></MyBody>
    <MyBody></MyBody>
    <MyBody></MyBody>
    <MyBody></MyBody>
  </div>
</template>

<script>
import Header from './components/Header'
import Body from './components/Body'

export default {
  components: {
    "MyHeader": Header,
    "MyBody": Body,
  }
}
</script>

<style scoped>

</style>