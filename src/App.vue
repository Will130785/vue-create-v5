<template>
  <div class="example">
    {{ msg }}
    <Test />
  </div>
</template>

<script>
import Test from './Test.vue'
export default {
  components: {
    Test
  },
  data () {
    return {
      msg: 'Hello world!!!!'
    }
  }
}
</script>

<style>
.example {
  color: red;
}
</style>
