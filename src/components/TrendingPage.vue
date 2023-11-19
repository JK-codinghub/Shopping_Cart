<template>
    <div class="Trend">
        <!-- Trending Title -->
        <h2 class="rowGap"><span class="font7">Trending T-Shirts</span></h2>

        <div class="row gx-0">

            <!-- Card 1 -->
            <div class="col-3 cardRow">
                <div class="card" style="width:264px;border:none;">
                    <img src="../assets/Rectangle 4.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <div class="row gx-0 d-flex justify-content-center">
                            <div class="col-7 text-center"> Men Henley Neck Full Sleeve Red Wine</div>
                            <div class="col-7 mt-1 d-flex align-items-center justify-content-center"><span
                                    class="newPrice">₹399</span><span class="oldPrice">₹1299</span></div>
                            <div class="col-12 mt-1">
                                <div class="row gx-0 d-flex justify-content-evenly">
                                    <div class="col-2 boxStyle d-flex align-items-center justify-content-center">S</div>
                                    <div class="col-2 boxStyle d-flex align-items-center justify-content-center">M</div>
                                    <div class="col-2 boxStyle d-flex align-items-center justify-content-center">L</div>
                                    <div class="col-2 boxStyle d-flex align-items-center justify-content-center">XL
                                    </div>
                                    <div class="col-2 boxStyle d-flex align-items-center justify-content-center">XXL
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>



        </div>
    </div>
</template>

<script>
    export default {
        name: "TrendingPage"
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
</style>