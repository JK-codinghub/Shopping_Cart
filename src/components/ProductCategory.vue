<template>
  <div class="categoryRow gx-0 scrolling-wrapper row flex-row flex-nowrap ">
    <div class=" col-sm-6 col-md-4 col-lg-2 col-xl-2" v-for="(category,index) in categoryLoop" :key="index">
        <div class="row gx-0">
            <div class="col-12 d-flex justify-content-center" :class="category.class">
             <img :src="require(`@/assets/${category.path}`) " width="170" height="170" alt="">    
            </div>       
            <div class="col-12 d-flex justify-content-center categoryStyle">{{category.name}}</div>
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
        {name:"Men’s T-Shirtsgory1", class:"ellipse", path:"Ellipse 7.png"},
        {name:"Women’s Wear", class:"ellipse", path:"Ellipse 8.png"},
        {name:"Winter Collections", class:"ellipse", path:"Ellipse 9.png"},
        {name:"Hooded T-Shirts", class:"ellipse", path:"Ellipse 10.png"},
        {name:"Polo Neck T-Shirts", class:"ellipse", path:"Ellipse 11.png"},
        {name:"Full Sleeves T-Shirts", class:"ellipse", path:"Ellipse 12.png"},
        {name:"Men’s T-Shirtsgory1", class:"ellipse", path:"Ellipse 7.png"},
        {name:"Women’s Wear", class:"ellipse", path:"Ellipse 8.png"},
        {name:"Winter Collections", class:"ellipse", path:"Ellipse 9.png"},
        {name:"Hooded T-Shirts", class:"ellipse", path:"Ellipse 10.png"},
        {name:"Polo Neck T-Shirts", class:"ellipse", path:"Ellipse 11.png"},
        {name:"Full Sleeves T-Shirts", class:"ellipse", path:"Ellipse 12.png"}
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
    visibility: hidden;
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
  margin: 0px 10px 0px 10px;
  border-radius: 170px;
}

</style>