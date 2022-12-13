
 <template>
    <div class="NavBar">
    <a class="nav-link active" aria-current="page" href="/">Home</a>    
    <a class="nav-link" href="Products">Products</a>
    <a class="nav-link" href="Contact">ContactForm</a>
    </div>
 </template>
 <script>
 export default {
    name: 'nav',

 }
 </script>
 
 <style scoped>

 .NavBar {
    text-align: center;
    background-color:rgb(0, 0, 0);
    width: 100%;
    display: flex;
    gap: 37rem;

 }
 a {
    color: white;
    
    font-size: 25px;
 }
    
 </style>