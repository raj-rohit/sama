<template>
<button class="alco">{{msg}}</button>
</template>

<script>
export default {
  name: 'Zero',
  props: {
    msg:{
      default:"AquaMan",
      type:String
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.alco {
  color:white;
  background-color: purple;
}
</style>
