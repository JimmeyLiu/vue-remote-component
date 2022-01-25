<template>
	<div id="app">
		<remote-component url="http://localhost:8080/dist/HelloWorld.js" />
	</div>
</template>

<script>
import RemoteComponent from "./RemoteComponent";

export default {
	name: "App",
	components: {
		RemoteComponent,
	},
};
</script>

<style>
</style>
