<template>
  <div id="app">dev分支ßrtr  我在github上修改de 
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<!--<style lang="less">
@nice-blue: #5B83AD;
@light-blue:@nice-blue;

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background:@light-blue;
}


</style>-->
<style lang="scss">
$nice_blue:red;
$light_blue:$nice_blue;
#app{
  background:$light_blue;
}


</style>
