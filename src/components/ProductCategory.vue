<template>
  <div class="row gx-0 bg-warning">
    <div class="col-2">
        <div class="row">
            <div class="col-12" :class="categoryLoop[0].class">
             <!-- <img :src="categoryLoop[0].path" width="170" height="170" alt="">     -->
            </div>       
            <div class="col-12 d-flex justify-content-start categoryStyle">{{categoryLoop[0].name}}</div>
        </div>
    </div>
  </div>
</template>

<script>
import { ref } from 'vue'
export default {
 name:"ProductCategory",
 setup() {
    const categoryLoop = ref([
        {name:"Men’s T-Shirtsgory1", class:"ellipse1", path:"../assets/Ellipse 7.png"}
    ]);
    return{
        categoryLoop
    }
 }
}
</script>

<style scoped>
.categoryStyle{
    margin-top: 20px;
    color: var(--Primary-Color_1, #1C1C1C);
    font-family: Playfair Display;
    font-size: 16px;
    font-style: normal;
    font-weight: 600;
}
.ellipse1{
  width: 170px;
  height: 170px;
  margin-right: 20px;
  border-radius: 170px;
  background: #F1DBE9  url("../assets/Ellipse 7.png"); 
  /*  background: #F1DBE9; */
}

</style>