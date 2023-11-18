<template>
  <div class="Home">
    <!--Header-->
    <div class="row m-0 p-0 headerRow d-flex justify-content-center">
      <div class="col-10 Heading font3 d-flex justify-content-start">
        <div class="col-6 d-flex align-items-center justify-content-start">
          Welcome to Our Store Hiscraves
        </div>
        <div
          class="col-6 d-flex align-items-center justify-content-end contactNum"
        >
          <img loading="lazy" src="../assets/phone.png" class="phone" />
          Call Us: 1234567890
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",
};
</script>

<style scoped>
.Home {
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
</style>
