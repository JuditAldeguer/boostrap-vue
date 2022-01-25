<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <div class="bg-info clearfix">
      <button type="button" class="btn btn-secondary float-left">Example Button floated left</button>
      <button type="button" class="btn btn-secondary float-right">Example Button floated right</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 60px 0 ;
  background-color: var(--body-color);
}

/* .float-left{
  float: left;
}
.float-right{
  float: right;
} */
</style>
