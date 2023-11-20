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

    <!-- Product Category2 -->
    <div class="row rowGap d-flex justify-content-center">
      <div class="col-10">  
        <ProductCategory2/>
      </div>
    </div>

    <!-- Banner 3 -->
    <div class="container-fluid rowGap m-0 p-0">
      <div class="col-12">
        <img src="../assets/banner3.jpg" style="width:100%" alt="">
      </div>
    </div>


    <!-- Deal -->
    <div class="row gx-0 d-flex justify-content-center">
      <div class="col-10">
        <div class="row gx-0 d-flex justify-content-center">
          <div class="card deal1 rowGap">
            <div class="row gx-0">
              <div class="col-12 d-flex justify-content-center">
                <img loading="lazy" src="../assets/diamond.jpg" class="deals" />
              </div>
              <div class="col-12 d-flex justify-content-center font7 message">Hurry Up!</div>
              <div class="col-12 d-flex justify-content-center font8 discount">85% OFF</div>
              <div class="col-12 d-flex justify-content-center font7 sale">Sale</div>
              <div class="col-12 d-flex justify-content-center mt-2"> <span
                  class="btn border border-light-1 text-light px-3 py-2 shopNow">SHOP NOW</span></div>
            </div>
          </div>
    
          <div class="card deal2 rowGap">
            <div class="row gx-0">
              <div class="col-12 d-flex justify-content-center">
                <img loading="lazy" src="../assets/Tag.jpg" class="deals" />
              </div>
              <div class="col-12 d-flex justify-content-center font7 message">Hurry Up!</div>
              <div class="col-12 d-flex justify-content-center font8 discount">75% OFF</div>
              <div class="col-12 d-flex justify-content-center font7 sale">Sale</div>
              <div class="col-12 d-flex justify-content-center mt-2"> <span
                  class="btn border border-light-1 text-light px-3 py-2">SHOP NOW</span></div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Services -->
    <div class="row rowGap services gx-0 d-flex justify-content-center">
      <div class="col-10">
        <div class="row gx-0">

          <div class="col-sm-6 col-md-3">
            <div class="row gx-0">
              <div class="col-12 d-flex justify-content-center">
                <img src="../assets/Group.jpg" alt="">
              </div>
              <div class="col-12  d-flex justify-content-center font4 serviceName">
                7 Days Return
              </div>
            </div>
          </div>

          <div class="col-sm-6 col-md-3 line">
            <div class="row gx-0">
              <div class="col-12 d-flex justify-content-center">
                <img src="../assets/Group 196.jpg" alt="">
              </div>
              <div class="col-12  d-flex justify-content-center font4 serviceName">
                Quality Products
              </div>
            </div>
          </div>

          <div class="col-sm-6 col-md-3 line">
            <div class="row gx-0">
              <div class="col-12 d-flex justify-content-center">
                <img src="../assets/Group 197.jpg" alt="">
              </div>
              <div class="col-12  d-flex justify-content-center font4 serviceName">
                Safe Payment
              </div>
            </div>
          </div>

          <div class="col-sm-6 col-md-3 line">
            <div class="row gx-0">
              <div class="col-12 d-flex justify-content-center">
                <img src="../assets/Group 198.jpg" alt="">
              </div>
              <div class="col-12  d-flex justify-content-center font4 serviceName">
                24x7 Helpline
              </div>
            </div>
          </div>

        </div>        
      </div>
    </div>

    <!-- Subscription -->
    <div class="row rowGap gx-0 d-flex justify-content-center">
      <div class="col-10 subscription">
       <div class="row gx-0  d-flex justify-content-center">
        <div class="col-8">
          <div class="row gx-0">
            <div class="col-12 subscribeTitle font7">Subscribe to get updates on exciting offers
              & deals</div>
            <div class="col-12 emailInput">
              <div class="input-group mb-3">
                <input type="text" class="form-control text-light" placeholder="Enter your email" aria-label="Email" aria-describedby="basic-addon2">
                <span class="input-group-text font6" id="basic-addon2"> Subscribe</span>
              </div>
            </div>
          </div>
        </div>
       </div>
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
import ProductCategory2 from './ProductCategory2.vue';

export default {
  name: "HomePage",
  components:{
    OffersPage,
    ProductCategory,
    FooterPage,
    TrendPage,
    FeaturedProduct,
    NewProducts,
    BestSellProducts,
    ProductCategory2
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
.font6 {
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

.deal1{
  width: 548px;
  height: 652px;
  background: #CCCEA7;
  margin-right:24px;
}

.deal2{
  width: 548px;
  height: 652px;
  background: #D6BEBE;
}
.deal1, .deal2:hover{
  cursor: pointer;
}
.btn:hover{
  opacity: 0.4;
}

.message:hover{
  font-size: 40px;
}
.discount:hover{
  font-size: 40px;
}

.deals{
  margin-top: 54.86px;
}

.message{
  margin-top: 48.27px;
  color: var(--Primary-Color_1, #1C1C1C);
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: 600;
}

.discount{
  margin-top: 22px;
  color: var(--Primary-Color_1, #1C1C1C);
  font-family: "Playfair Display";
  font-weight: 600;
}

.sale{
  margin-top: 22px;
  color: var(--Primary-Color_1, #1C1C1C);
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: 600;
}
.shopNow{
  margin-bottom: 54.86px;
}

@media(min-width: 1200px) {
  .deal1{
    width: 548px;
    height: 652px;
  }
  .deal2{
    width: 548px;
    height: 652px;
  }
}

.services{
  background: #F5F4F2;
  padding: 39.15px 0px;
}
.serviceName{
  margin-top: 25px;
  color: var(--Primary-Color_1, #1C1C1C);
  font-family: "Montserrat"; 
  font-weight: 500;
}
.line{
  border-left: 1px solid #FFC7D1;
}
.subscription{
 padding:60.42px 0px;
 background: linear-gradient(97deg, #AB001E -6.23%, #770015 105.09%);
}
.subscribeTitle{
  color: #FFF;
  text-align: center;
  font-family: "Playfair Display";
  font-weight: 600;
  margin-bottom: 27.16px;
  width: 694px !important;
}
.form-control{
  height: 68px;
  padding: 24px 28.5px;
  background: rgba(255, 255, 255, 0.32);
}

.form-control::placeholder{
  color: #FFF;
  font-weight: normal;
}
.input-group-text{
  background: #FFF;
  color: #770015;
  font-weight: 500;
}
</style>
