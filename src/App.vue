<template>
<div id="app" class="animate__animated animate__fadeIn">
  
  <Encode class="en animate__animated animate__backInLeft"/>
  <Decode class="de animate__animated animate__backInRight"/>

</div>
</template>

<script>
import Encode from './components/Encode.vue'
import Decode from './components/Decode.vue'
export default {
  name: 'App',
  components: {
    Encode,Decode
  }
}
</script>

<style lang="scss">
body {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 60px;
  background-color: #4e4c4c7e;
 #app {
   .en {
     margin: 7px;
     box-shadow: -15px 15px 35px black;
   }
   .de {
     margin: 7px;
     box-shadow: 15px 15px 35px black;
   }
  display: flex;
  grid-template-columns: repeat(2,250px);
 }
}


</style>
