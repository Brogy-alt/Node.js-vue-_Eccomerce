<template>
<nav-bar></nav-bar>
  <div class="home">
    <img class="home-img" alt="Website logo" src="https://i.postimg.cc/P5D2vvHG/home-imge.jpg">
    <HelloWorld msg="Pick your Kick"/>
  </div>

  <div>
    <footer>
      
    </footer>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import NavBar from '@/components/NavBar.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    NavBar,Footer
    
}
}


</script>

<style>
.home-img{
  width: 100vw;
  height: 100vh;
  
}

</style>

