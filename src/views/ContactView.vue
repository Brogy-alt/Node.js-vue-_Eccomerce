<template>
    <nav-bar></nav-bar>
    <body>
        
    <products/>


    <div>
    
    <Contact/>

    </div>

    <div>
    <footer>
      
    </footer>
</div>
</body>
</template>
<script>


import NavBar from '@/components/NavBar.vue';
import Footer from '@/components/Footer.vue';
import Contact from '@/components/ContactForm.vue';

export default {
    components: {
    NavBar,
    Footer,
    Contact
    }
}


</script>


<style>

    
</style>