<template lang="">
  <div>
    <h2>{{greet}} {{name}}</h2>
  </div>
  <div v-text="channel"></div>
  <div v-text="name"></div>
</template>
<script>
export default {
  name:"App",
  data() {
    return {
      greet: "Hello",
      name:"M.Ferdawus",
      channel:"Codevolution"
    }
  },
}
</script>
<style lang="">
  
</style>