<template>
    <section id="items">
<div style="display:grid; grid-template-columns: repeat(3,1fr)">
<div class="card" v-for="item in products" :key="item" style="width: 18rem;" >
  <img :src="item.img" class="card-img-top" alt="images">
  <div class="card-body">
    <h5 class="card-title">{{item.shoeName}}</h5>
    <p class="card-text">{{item.shoeSize}}</p>
    <p class="card-text2">{{item.price}}</p>
    <a href="#" class="btn btn-primary">Buy</a>
  </div>
</div>
</div>
</section>
<!-- <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel" ">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img :src="" class="d-block w-100" alt="images">
    </div>
</div>
</div>
     -->
</template>

<script>


export default {
    name : 'products',

    data (){
        return {
            products : [
        {
         shoeName: 'Brand : Nike',
         shoeSize: 'Size 12',
         price: 'R1799',
         img: 'https://i.postimg.cc/j2qfLs9p/Image1.jpg'
        },
        {
         shoeName: 'Brand : Puma',
         shoeSize: 'Size 11',
         price: 'R2000',
         img: 'https://i.postimg.cc/CKYTzNbf/Image3.jpg'
        },
        {
         shoeName: 'Brand : Fila',
         shoeSize: 'Size 10',
         price: 'R2700',
         img: 'https://i.postimg.cc/25CMz5fQ/image2.png'
        }
 ]
}
 } 
}







</script >
<style scoped>
#items{
    height: 100vh;
    width: 100vw;
    padding-left: 10rem;
    margin-top: 10rem;

    
}


    
</style>