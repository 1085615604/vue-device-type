<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    <device-type :username="nickname"></device-type>
  </div>
</template>

<script>
import deviceType from '../src/myPlugin/getDeviceType/device-type'

export default {
  name: 'app',
  components: {
    deviceType
  },
  data () {
    return {
      msg: 'home',
      nickname: '张三'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
