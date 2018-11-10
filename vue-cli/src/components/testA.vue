<template>
  <div>
    <h2>test AAAAA</h2>
    <testB></testB>
  </div>
</template>

<script>
//import 引入其它的模块   export 模块对外的接口
import testB from './testB'
export default {
  //name: 'App',
  components: {
    //HelloWorld
    testB
  }
}
// var name="sonia";
// var age = 18;
// function add(x,y){
//     alert(x+y);
// };
//导出多个
//export {name,age,add};
//仅有一个 
// export default {  
//     name:'abc',
//     hobby:'games'
// }
</script>

<style>

</style>
