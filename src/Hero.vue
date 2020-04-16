<template>
<button class="alco">{{msg}}</button>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg:{
      default:"Heman",
      type:String
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.alco {
  color: #42b983;
  background-color: black;
}
</style>
