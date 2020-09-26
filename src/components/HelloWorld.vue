<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <Button>Test Button</Button>

    <br />
    <br />

    <Button href="https://google.com">Test Button</Button>
  </div>
</template>

<script>
import Button from './Button.vue'

export default {
  name: 'HelloWorld',
  components: { Button },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #42b983;
}
</style>
