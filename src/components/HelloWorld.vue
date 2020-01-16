<template>
  <div class="hello">
    <h1>{{ txt }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      txt: 'Welcome to my first vueProject'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  div{
    background: red;
  }

</style>
