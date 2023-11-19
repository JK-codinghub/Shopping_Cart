<template>
    <div class="newProduct">
        <!-- New Product Title -->
        <h2 class="rowGap"><span class="font7">New Products</span></h2>

        <div class="row gx-0">
            <!-- Card  -->
            <div class="col-sm-8 col-md-6 col-lg-6 col-xl-3 cardRow" v-for="(product, index) in productList.splice(0,4)"
                :key="index">
                <div class="card" style="width:264px;border:none;">
                    <img :src="require(`@/assets/${product.image}`) " class="card-img-top card_image" alt="...">

                    <div class="overlay">
                        <a href="#" class="button d-flex align-items-center justify-content-center">
                            <i class="bi bi-cart3 istyle"></i>
                        </a>
                        <a href="#" class="button d-flex align-items-center justify-content-center">
                            <i class="bi bi-heart-fill istyle"></i>
                        </a>
                        <a href="#" class="button d-flex align-items-center justify-content-center">
                            <i class="bi bi-share-fill istyle"></i>
                        </a>
                    </div>

                    <div class="card-body">
                        <div class="row gx-0 d-flex justify-content-center">
                            <div class="col-10 text-center"> {{product.name}}</div>
                            <div class="col-7 mt-1 d-flex align-items-center justify-content-center"><span
                                    class="newPrice">₹{{ product.newPrice }}</span><span class="oldPrice">₹{{
                                    product.oldPrice}}</span></div>
                            <div class="col-12 mt-1">
                                <div class="row gx-0 d-flex justify-content-evenly">
                                    <div class="col-2 boxStyle d-flex align-items-center justify-content-center"
                                        v-for="size in sizes" :key="size">
                                        {{ size.listCode}}
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="row gx-0 d-flex align-items-center justify-content-center" style="margin-top: 48.11px;">
            <div class="btn btnStyle d-flex align-items-center justify-content-center">VIEW ALL</div>
        </div>
    </div>
</template>

<script>
    import { ref } from 'vue';
    export default {
        name: "NewProducts",
        setup() {
            const productList = ref([
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 3.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 4.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 5.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 6.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 3.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 4.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 5.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 6.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 3.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 4.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 5.jpg" },
                { name: "Men Henley Neck Full Sleeve Red Wine", newPrice: "399", oldPrice: "1299", image: "Rectangle 6.jpg" },
            ]);

            const sizes = ref([
                { listName: "Small", listCode: "S" },
                { listName: "Medium", listCode: "M" },
                { listName: "Large", listCode: "L" },
                { listName: "X-Large", listCode: "XL" },
                { listName: "XX-Large", listCode: "XXL" },
            ])
            return {
                productList,
                sizes
            }
        }
    }
</script>

<style scoped>
    .font3 {
        font-size: 14px;
    }

    .font7 {
        font-size: 36px;
    }

    h2 {
        width: 100%;
        text-align: center;
        border-bottom: 1px solid #FFC7D1;
        line-height: 0.1em;
        margin: 10px 0 20px;
    }

    .cardRow {
        margin-top: 48.11px;
    }

    h2 span {
        background: #fff;
        padding: 0 10px;
        color: var(--Primary-Color_1, #1C1C1C);
        font-family: Playfair Display;
        font-weight: 600;
    }

    .newPrice {
        color: #1F1F1F;
        font-size: 18px;
        font-style: normal;
        font-weight: 700;
        line-height: 18px;
        margin-right: 3px;
    }

    .oldPrice {
        color: #F00;
        font-size: 10px;
        font-style: normal;
        font-weight: 400;
        line-height: 18px;
        text-decoration-line: strikethrough;
    }

    .boxStyle {
        width: 36px;
        height: 36px;
        border: 1px solid #E6E6E6;
    }


    .card {
        position: relative;
        overflow: hidden;
    }

    .card img {
        width: 264px;
        height: 412px;
        transition: transform 0.4s;
    }

    .card:hover img {
        transform: scale(1);
    }

    .overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 264px;
        height: 412px;
        display: flex;
        align-items: center;
        justify-content: center;
        background: rgba(31, 31, 31, 0.30);
        backdrop-filter: blur(5px);

        opacity: 0;
        transition: opacity 0.5s;
    }

    .card:hover .overlay {
        opacity: 1;
    }

    a {
        width: 54px;
        height: 54px;
        border-radius: 27px;
        margin-right: 10px;
        text-decoration: none;
        background-color: white;
        cursor: pointer;
    }

    .istyle {
        font-size: 26px;
        color: #770015
    }

    .btnStyle {
        width: 170px;
        height: 48px;
        color: #FFF;
        font-size: 16px;
        font-style: normal;
        font-weight: 500;
        background: #770015;
        cursor: pointer;
    }
</style>