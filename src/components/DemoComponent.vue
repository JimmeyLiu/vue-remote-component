<template>
  <div class="hello">
    这是DemoComponent组件
    <remote-component url="http://localhost:8080/static/HelloWorld.js"/>
  </div>
</template>

<script>
import RemoteComponent from '../RemoteComponent'
export default {
	components: { RemoteComponent },
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App发生发大水'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
.hello{
  font-size: 30px;
  color: red;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
