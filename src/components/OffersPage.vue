<template>
  <div class="m-0 p-0">
    <div class="row gx-0">
      <div class="col-6">
        <img loading="lazy" src="../assets/image 2.jpg" class="offerImg1 mr-2" alt="Image not loading">
      </div>
      <div class="col-6">
        <img loading="lazy" src="../assets/image 3.jpg" class="offerImg2" alt="Image not loading">
      </div>
    </div>

    <div class="row gx-0 offerRow2">
      <div class="col-4">
        <img loading="lazy" src="../assets/image 4.jpg" class="offerImg4" alt="Image not loading">
      </div>
      <div class="col-4">
        <img loading="lazy" src="../assets/image 6.jpg" class="offerImg5" alt="Image not loading">
      </div>
      <div class="col-4">
        <img loading="lazy" src="../assets/image 5.jpg" class="offerImg6" alt="Image not loading">
      </div>
    </div>

  </div>

</template>

<script>
  export default {
  name:"OffersPage"
  }
</script>

<style scoped>

.offerImg1{
  margin-right: 20px;
}
.offerImg1:hover{
  cursor: pointer;
}
.offerImg2:hover{
  cursor: pointer;
}

img:hover{
  opacity: 0.4;
}

.offerRow2{
  margin-top: 16px;
}
 /* Small devices ( phones, less than 768px) */
@media (min-width: 568px) { 
    .offerImg1{
      width:235px;
      height: 120px;
    }
    .offerImg2{
      width:235px;
      height: 120px;
    }
    .offerImg4{
      width:159px;
    }
    .offerImg5{
      width: 140px;
      height: 77px;
    }
    .offerImg6{
      width:159px;
    }
 }

 /* Medium devices (768px) */
@media (min-width: 768px) { 
  .offerImg1{
      width:315px;
      height: 170px;
    }
    .offerImg2{
      width:315px;
      height: 170px;
    }
    .offerImg4{
      width:209px;
    }
    .offerImg5{
      width:200px;
      height:102px;
    }
    .offerImg6{
      width:209px;
    }
 }

/* Large devices (992px) */
@media (min-width: 992px) { 
  .offerImg1{
      width:405px;
      height: 220px;
    }
    .offerImg2{
      width:405px;
      height: 220px;
    }
    .offerImg4{
      width:269px;
    }
    .offerImg5{
      width:260px;
      height:131.5px;
    }
    .offerImg6{
      width:269px;
    }
 }

/* Large devices (desktops, less than 1200px) */
@media (min-width: 1200px) and (max-width:1365px) { 
  .offerImg1{
      width:492px;
      height: 250px;
    }
    .offerImg2{
      width:492px;
      height: 250px;
    }
    .offerImg4{
      width:329px;
    }
    .offerImg5{
      width:320px;
      height:160px;
    }
    .offerImg6{
      width:329px;
    }
 }

 /* Custom Screen size */
@media (min-width: 1366px) {
  .offerImg1{
    width:550px;
    height: 276px;
  }
  .offerImg2{
    width:550px;
    height: 276px;
  }
  .offerImg4{
      width:360px;
    }
    .offerImg5{
      width:360px;
      height:176px;
    }
    .offerImg6{
      width:360px;
    }
}

 /* XXL Screen size */
 @media (min-width: 1400px) {
  .offerImg1{
    width:570px;
    height: 276px;
  }
  .offerImg2{
    width:580px;
    height: 276px;
  }
  .offerImg4{
      width:383px;
    }
    .offerImg5{
      width:375px;
      height:187px;
    }
    .offerImg6{
      width:383px;
    }
}

</style>