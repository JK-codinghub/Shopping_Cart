<template>
  <div class="categoryRow gx-0 scrolling-wrapper row flex-row flex-nowrap ">
    <div class="col-2" v-for="(category,index) in categoryLoop" :key="index">
        <div class="row gx-0">
            <div class="col-12" :class="category.class">
             <!-- <img :src="categoryLoop[0].path" width="170" height="170" alt="">     -->
            </div>       
            <div class="col-12 d-flex justify-content-start categoryStyle">{{category.name}}</div>
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
        {name:"Men’s T-Shirtsgory1", class:"ellipse category1", path:"../assets/Ellipse 7.png"},
        {name:"Women’s Wear", class:"ellipse category2", path:"../assets/Ellipse 8.png"},
        {name:"Winter Collections", class:"ellipse category3", path:"../assets/Ellipse 9.png"},
        {name:"Hooded T-Shirts", class:"ellipse category4", path:"../assets/Ellipse 10.png"},
        {name:"Polo Neck T-Shirts", class:"ellipse category5", path:"../assets/Ellipse 11.png"},
        {name:"Full Sleeves T-Shirts", class:"ellipse category6", path:"../assets/Ellipse 12.png"},
        {name:"Men’s T-Shirtsgory1", class:"ellipse category1", path:"../assets/Ellipse 7.png"},
        {name:"Women’s Wear", class:"ellipse category2", path:"../assets/Ellipse 8.png"},
        {name:"Winter Collections", class:"ellipse category3", path:"../assets/Ellipse 9.png"},
        {name:"Hooded T-Shirts", class:"ellipse category4", path:"../assets/Ellipse 10.png"},
        {name:"Polo Neck T-Shirts", class:"ellipse category5", path:"../assets/Ellipse 11.png"},
        {name:"Full Sleeves T-Shirts", class:"ellipse category6", path:"../assets/Ellipse 12.png"}
    ]);
    return{
        categoryLoop
    }
 }
}
</script>

<style scoped>

.scrolling-wrapper{
	overflow-x: auto;
}
::-webkit-scrollbar{
    display: none;
}
.categoryStyle{
    margin-top: 20px;
    color: var(--Primary-Color_1, #1C1C1C);
    font-family: Playfair Display;
    font-size: 16px;
    font-style: normal;
    font-weight: 600;
}
.ellipse{
  width: 170px;
  height: 170px;
  margin-right: 20px;
  border-radius: 170px;
}
.category1{
  background: #F1DBE9  url("../assets/Ellipse 7.png"); 
}
.category2{
  background: #F1DBE9  url("../assets/Ellipse 8.png"); 
}
.category3{
  background: #F1DBE9  url("../assets/Ellipse 9.png"); 
}
.category4{
  background: #F1DBE9  url("../assets/Ellipse 10.png"); 
}
.category5{
  background: #F1DBE9  url("../assets/Ellipse 11.png"); 
}
.category6{
  background: #F1DBE9  url("../assets/Ellipse 12.png"); 
}



</style>