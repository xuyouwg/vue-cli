<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!--<HelloWorld/>-->
    <!--{{name.hobby}}-->
    <testA></testA>
  </div>
</template>

<script>
//import 引入其它的模块   export 模块对外的接口
//import HelloWorld from './components/HelloWorld'
//export {name,age,add} 引用方式
//import {name,age,add} from './components/testA'
//export default  引用方式
//import obj from './components/testA'
import testA from './components/testA'

export default {
  name: 'App',
  data(){
    return {
      //name:obj
    }
  },
  components: {
    //HelloWorld,
    testA
  },
  mounted(){
   // add(2,3);
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
</style>
