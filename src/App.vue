<template>
	<div id="app">
		<remote-component url="http://localhost:8080/dist/HelloWorld.js" />
	</div>
</template>

<script>
import RemoteComponent from "./RemoteComponent.vue";

export default {
	name: "App",
	components: {
		RemoteComponent,
	},
};
</script>

<style
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
