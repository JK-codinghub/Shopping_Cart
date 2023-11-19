<template>
    <div class="Footer m-0 p-0">
        <div class="row gx-0">

            <!-- Summary -->
            <div class="col-sm-12 col-md-12 col-lg-4 mb-4">
                <div class="row gx-0">
                    <div class="col-12 d-flex justify-content-start summary font3 ">
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been
                        the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley
                        of type and scrambled it to make a type specimen book. It has survived not only five
                        centuries....
                    </div>

                    <!-- Icons Row -->
                    <div class="col-12 mt-1 d-flex justify-content-start">
                        <!-- Facebook  -->
                        <i class="bi bi-facebook iconStyle facebook" size="2px"></i>

                        <!-- Twitter -->
                        <i class="bi bi-twitter iconStyle twitter"></i>

                        <!-- Instagram -->
                        <i class="bi bi-instagram iconStyle instagram"></i>

                        <!-- LinkeIn  -->
                        <i class="bi bi-linkedin iconStyle linkedIn"></i>

                        <!-- Pinterest  -->
                        <i class="bi bi-pinterest iconStyle pinterest"></i>

                    </div>
                </div>
            </div>

            <!-- Links -->
            <div class="col-sm-12 col-md-12 col-lg-2 mb-4">
                <div class="row gx-0">
                    <div class="col-12 title">ONLINE SHOPPING</div>

                    <div class="col-12 listRow  font3">Men’s T-Shirts</div>
                    <div class="col-12 font3">Women’s Wear</div>
                    <div class="col-12 font3">Winter Collections</div>
                    <div class="col-12 font3">Hooded T-Shirts</div>
                    <div class="col-12 font3">Streetwear Collections</div>

                </div>
            </div>
            <div class="col-sm-12 col-md-12 col-lg-3 mb-4">
                <div class="col-12 title">CUSTOMER POLICIES</div>

                <div class="col-12 listRow font3">About Us</div>
                <div class="col-12 font3">Terms & Conditions</div>
                <div class="col-12 font3">Shipping & Returns Policy</div>
                <div class="col-12 font3">Cancellation & Refund Policy</div>
                <div class="col-12 font3">Contact Us</div>
            </div>

            <div class="col-sm-12 col-md-12 col-lg-3 mb-4">
                <div class="col-12 title">STORE INFORMATION</div>


                <div class="col-12 listRow font3"><i class="bi bi-geo-alt smallIcons"></i> Lorem Ipsum is simply dummy
                    text of the
                    printing and typesetting industry.
                </div>
                <div class="col-12 listRow font3"><i class="bi bi-telephone smallIcons"></i> Call Us: 1234567890
                </div>
                <div class="col-12 listRow font3"><i class="bi bi-envelope smallIcons"></i> Email Us: info@yourmail.com
                </div>

            </div>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
    .Footer {
        width: 100%;
    }

    .font3 {
        font-size: 14px;
    }

    .summary {
        width: 360px !important;
        color: var(--Primary-Color_1, #1C1C1C);
        font-style: normal;
        font-weight: 500;
        line-height: 28px;
        /* 200% */
    }

    .iconStyle {
        width: 46px;
        height: 46px;
        border-radius: 23px;
        margin-right: 13.75px;
        font-size: 25px;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .smallIcons {
        width: 24px;
        height: 24px;
        flex-shrink: 0;
        margin-right: 5px;
    }

    .facebook {
        background: #1077F0;
        color: white;
    }

    .twitter {
        background: #229AEF;
        color: white;
    }

    .instagram {
        /* background: #FFDB70, #F3278E, #5351D7; */
        background: linear-gradient(115deg, #f9ce34, #ee2a7b, #6228d7);
        color: white;
    }

    .linkedIn {
        background: #2B67B3;
        color: white;
    }

    .pinterest {
        background: #E60022;
        color: white;
    }

    .title {
        color: #770015;
        font-family: "Playfair Display";
        font-size: 18px;
        font-style: normal;
        font-weight: 600;
        line-height: normal;
    }

    .listRow {
        margin-top: 29.33px;
    }
</style>