<template>
  <div class="wrapper">
      <Hero/>
  </div>
</template>

<script>
import Hero from './Hero'


export default {
    name: 'Main',
    components:{
        Hero,
    }
}
</script>

<style scoped>
    .wrapper{
        border: 5px dotted yellow;
    }

</style>