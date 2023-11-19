<template>
  <div class="Home m-0 p-0">
    <!--Header-->
    <div class="row m-0 headerRow d-flex justify-content-center">
      <!-- Heading Row -->
      <div class="col-10 Heading font3 d-flex justify-content-start">
        <div class="col-6 d-flex justify-content-start">
          Welcome to Our Store Hiscraves
        </div>
        <div
          class="col-6 d-flex justify-content-end contactNum"
        >
          <img loading="lazy" src="../assets/phone.png" class="phone" />
          Call Us: 1234567890
        </div>
      </div>   
    </div>

    <!-- Navigation Row -->
    <div class="row m-0 navigRow  d-flex justify-content-center">
      <div class="col-10 d-flex justify-content-between">
        <div class="d-flex justify-content-start">
          <img src="../assets/menubar.png" class="navbarIcon" alt="Image not loading">
        </div>
        <div class="logo font4 d-flex align-items-center">Logo Here</div>
        <div class="d-flex d-flex justify-content-end">
          <span class="navlinks"> <img src="../assets/search.png" alt=""> </span>
          <span class="navlinks"> <img src="../assets/likes.png" alt=""> </span>
          <span class="navlinks"> <img src="../assets/shopping-bag.png" alt=""> </span>
          <span class="navlinks"> <img src="../assets/user-icon.png" alt=""> </span>
        </div>
      </div>
    </div>

    <!-- Banner 1 -->
    <div class="container-fluid m-0 p-0">
      <div class="col-12">
        <img src="../assets/banner1.jpg" style="width:100%" alt="">
      </div>
    </div>

    <!-- Poduct Category -->
    <div class="row gx-0 rowGap d-flex justify-content-center">
      <div class="col-10">
        <ProductCategory/>
      </div>
    </div>

    
    <!-- Offers -->
    <div class="row rowGap gx-0 d-flex justify-content-center">
      <div class="col-10 d-flex justify-content-start">
        <OffersPage/>
      </div>
    </div>

    <!-- Trending Product Page -->
    <div class="row rowGap d-flex justify-content-center">
      <div class="col-10">
        <TrendPage/>
      </div>
    </div>

    <!-- Featured Product Page -->
    <div class="row rowGap d-flex justify-content-center">
      <div class="col-10">
        <FeaturedProduct/>
      </div>
    </div>

    <!-- Banner 2 -->
    <div class="container-fluid rowGap m-0 p-0">
      <div class="col-12">
        <img src="../assets/banner2.jpg" style="width:100%" alt="">
      </div>
    </div>

    <!-- New Product Page -->
    <div class="row rowGap d-flex justify-content-center">
      <div class="col-10">
        <NewProducts/>
      </div>
    </div>

    <!-- Best Selling Product Page -->
    <div class="row rowGap d-flex justify-content-center">
      <div class="col-10">
        <BestSellProducts/>
      </div>
    </div>

    <!-- Banner 3 -->
    <div class="container-fluid rowGap m-0 p-0">
      <div class="col-12">
        <img src="../assets/banner3.jpg" style="width:100%" alt="">
      </div>
    </div>

    <div class="horizontalRow rowGap"></div>

    <!-- Footer summary Page  -->
    <div class="row rowGap gx-0 d-flex justify-content-center">
      <div class="col-10">
        <FooterPage/>
      </div>
    </div>

    <!-- Footer -->
    <div class="row gx-0 d-flex align-items-center justify-content-center font3"
      style="background: #20050A;color:white; height: 68px;">
      ©2022-23 Powered By dummy team
    </div>

  </div>
</template>

<script>
 
import OffersPage from './OffersPage.vue';
import ProductCategory from './ProductCategory.vue';
import FooterPage from './FooterPage.vue';
import TrendPage from './TrendingPage.vue';
import FeaturedProduct from './FeaturedProduct.vue';
import NewProducts from './NewProducts.vue';
import BestSellProducts from './BestSellProducts.vue';

export default {
  name: "HomePage",
  components:{
    OffersPage,
    ProductCategory,
    FooterPage,
    TrendPage,
    FeaturedProduct,
    NewProducts,
    BestSellProducts
  }
};
</script>

<style scoped>
.Home {
  width: 100%;
  height: 100%;
  overflow-y: scroll;
  font-family: "Montserrat";
  font-style: normal;
  /* width: 1366px; */
}
.font1 {
  font-size: 10px;
}
.font2 {
  font-size: 12px;
}
.font3 {
  font-size: 14px;
}
.font4 {
  font-size: 16px;
}
.font5 {
  font-size: 18px;
}
font6 {
  font-size: 22px;
}
.font7 {
  font-size: 36px;
}
.font8 {
  font-size: 84px;
}
.headerRow {
  background: #1f1f1f;
  color: white;
}
.Heading {
  padding: 15.5px 0px 15.5px 0px;
}
.phone {
  width: 24px;
  height: 24px;
  margin-right: 8px;
}
.contactNum {
  margin-right: 16px;
}
.navigRow {
  padding: 32px 0px 32px 0px;
}
.navbarIcon{
  width: 24px;
  height: 24px;
}
.logo{
  color: var(--Primary-Color_1, #1C1C1C);
font-family: "Playfair Display";
font-size: 16px;
font-style: normal;
font-weight: 600;
line-height: normal;
}
.navlinks{
  margin-left:24.67px;
}

.horizontalRow{
  background-color: #e0dfde;
  align-self: stretch;
  min-height: 1px;
  width: 100%;
}

.rowGap{
  margin-top: 68px !important;
}
</style>
