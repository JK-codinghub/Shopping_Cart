<template>
  <div class="Category_2 m-0 p-0">
    <!-- Product Types -->
    <div class="row gx-0 d-flex justify-content-between">
      <div class="card" v-for="product in productList.splice(0,6)" :key="product">
        <img :src="require(`@/assets/${product.image}`)" class="card-img-top" alt="">
        <div class="overlay">
          <div class="productType d-flex align-items-center justify-content-center">{{product.name}}</div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
  import { ref } from 'vue';
  export default {
    name: "ProductCategory2",
    setup() {
      const productList = ref([
        { name: "Streetwear Collectionse", image: "Rectangle 18.jpg" },
        { name: "Streetwear Collectionse", image: "Rectangle 19.jpg" },
        { name: "Streetwear Collectionse", image: "Rectangle 20.jpg" },
        { name: "Streetwear Collectionse", image: "Rectangle 21.jpg" },
        { name: "Streetwear Collectionse", image: "Rectangle 22.jpg" },
        { name: "Streetwear Collectionse", image: "Rectangle 23.jpg" },
      ]);


      return {
        productList
      }
    }
  }
</script>

<style scoped>
  .productType {
    color: #FFF;
    font-family: "Playfair Display";
    font-size: 20px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    padding: 20.62px 0px;
  }

  .card {
    width: 360px;
    position: relative;
    margin-bottom: 20px;
  }

  img {
    height: 432px;
  }

  .overlay {
    position: absolute;
    bottom: 0px;
    width: 360px;
    height: 68.234px;
    background: linear-gradient(111deg, rgba(255, 255, 255, 0.40) -8.95%, rgba(255, 255, 255, 0.01) 114%);
    backdrop-filter: blur(32px);
  }

  .overlay:hover {
    background: black;
    backdrop-filter: none;
  }



  @media (min-width:992px) {
    .card {
      width: 250px;
    }

    .overlay {
      width: 247px;
    }
  }

  @media (min-width:1200px) {
    .card {
      width: 310px;
    }

    .overlay {
      width: 307px;
    }
  }

  @media (min-width:1366px) {
    .card {
      width: 360px;
    }

    .overlay {
      width: 357px;
    }
  }

  @media (min-width:1400px) {
    .card {
      width: 380px;
    }

    .overlay {
      width: 377px;
    }
  }
</style>