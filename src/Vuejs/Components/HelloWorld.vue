<template>
  <div class="hello container">
    <h1>{{ msg }}</h1>
    <p class="button-red">Welcome</p>
     <p class="button-blue">Welcome</p>
    <img src="../../images/quote.png" />
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="css">
.container{
  border-width:5px;
  border-color:red;
  border-style:solid;
}

</style>
