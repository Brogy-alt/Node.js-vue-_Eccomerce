<template>
<nav-bar></nav-bar>
    <body>
        
    <products/>

    <div>
    <footer>
      
    </footer>

  </div>
</body>
</template>
<script>

import NavBar from '@/components/NavBar.vue';
import Footer from '@/components/Footer.vue';
import Products from '@/components/Products.vue';

export default {
  components: {
   NavBar,Products,Footer
    
}
}

</script>
<style lang="">
    
</style>