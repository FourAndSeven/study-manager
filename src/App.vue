<template>
  <div id="app">
    <img src="./assets/logo.png">
    <p class="jj">click</p>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
$(function(){
	$('.jj').click(function(){
		alert(1)
	})
})
</script>

<style lang="scss">
$color:#153;
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $color;
  margin-top: 60px;
}
</style>
