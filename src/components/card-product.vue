<template>
    <div class="product-card card">
        <div class="card-title wrap-1">Continental <br> PremiumContact<sup>TM</sup> 6</div>
        <div class="wrap-box wrap-2">
            <div class="appr-tag">
                <img src="../assets/tag.png" alt="APPR Tag"/>
            </div>
        </div>
        <div class="wrap-box wrap-3">
            <div class="label">205/55 R16 H</div>
            <div class="label">SUV</div>
        </div>
        <div class="wrap-box wrap-4">
            <div class="label">Stock <i class="fas fa-check check-icon"></i></div>
        </div>
        <div class="wrap-box wrap-5">
            <div class="label">Price <span>$340</span></div>
        </div>
        <div class="wrap-box wrap-6">
            <div class="add-cart-count">
                <div class="box"><i class="fas fa-minus"></i></div>
                <div class="box">4</div>
                <div class="box"><i class="fas fa-plus"></i></div>
            </div>
        </div>
        <div class="wrap-box wrap-7">
            <div class="label">Total <span class="total-value">$1,360</span><span class="save-value">Save $360</span></div>
        </div>
        <div class="wrap-box wrap-8">
            <div class="add-count-cta">
                <button type="button" class="add-cart-cta">
                    <i class="fas fa-cart-plus cart-plus"></i>
                    <span class="add-cta-text">Add to Cart</span>
                </button>
            </div>
        </div>
    </div>
</template>
<style scoped>
.card {
    background-color: #fff;
    position: relative;
    margin-bottom: 15px;
}
.product-card {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 15px;
}
.card-title {
    font-weight: bold;
    text-decoration: underline;
    margin-bottom: 10px;
}
.add-cart-count {
    display: flex;
    align-items: center;
    justify-content: center;
    max-width: 102px;
    border: 1px solid #e2e2e2;
    border-radius: 3px;
}
.add-cart-count .box {
    font-size: 12px;
    font-weight: bold;
    width: 34px;
    height: 34px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.add-cart-count .box:not(:last-child) {
    border-right: 1px solid #e2e2e2;
}
.add-cart-count .box:first-child,
.add-cart-count .box:last-child {
    cursor: pointer;
}
.add-cart-count .box:nth-child(2) {
    background-color: #e2e2e2;
}
.add-count-cta .add-cart-cta {
    color: #000;
    background-color: orange;
    font-size: 12px;
    font-weight: bold;
    display: flex;
    align-items: center;
    justify-content: center;
    min-width: 75px;
    border: 0;
    border-radius: 18px;
    padding: 6px 15px;
    cursor: pointer;
}
.add-count-cta .cart-plus {
    font-size: 20px;
    margin-right: 5px;
}
.wrap-box .label {
    margin-bottom: 5px;
}
.total-value {
    font-size: 15px;
    font-weight: bold;
    margin-left: 2px;
}
.appr-tag {
    max-width: 60px;
}
.appr-tag img {
    width: 100%;
}
.check-icon,
.into-icon,
.alert-icon {
    color: #fff;
    font-size: 12px;
    border-radius: 100%;
    padding: 2px;
}
.check-icon {
    background-color: green;
}
.into-icon {
    background-color: #d93551;
}
.alert-icon {
    background-color: orange;
}
.save-value {
    color: #d93551;
    display: none;
    margin-top: 5px;
}
@media (max-width: 992px) {
    .add-cta-text {
        /* display: none; */
    }
    .product-card {
        width: 49%;
        flex-flow: row wrap;
    }
    .wrap-1 {
        width: 50%;
        order: 1;
        margin-bottom: 5px;
    }
    .wrap-2 {
        width: 26%;
        order: 3;
        margin-bottom: 5px;
    }
    .wrap-3 {
        width: 50%;
        order: 2;
    }
    .wrap-4 {
        width: 24%;
        order: 4;
    }
    .wrap-5 {
        width: 22%;
        order: 5;
        
    }
    .wrap-4 .label,
    .wrap-5 .label {
        display: flex;
        justify-content: space-between;
        flex-direction: column;
    }
    .wrap-4 .label .check-icon,
    .wrap-5 .label span {
        margin-top: 5px;
    }
    .wrap-4 .label .check-icon {
        margin-left: 10px;
    }
    .save-value {
        display: block;
    }
    .wrap-6 {
        width: 50%;
        order: 7;
    }
    .wrap-7 {
        width: 28%;
        order: 6;
    }
    .wrap-7 .label {
        white-space: nowrap;
    }
    .wrap-8 {
        width: 50%;
        order: 8;
    }
}
@media (max-width: 767px) {
    .product-card {
        width: 100%;
    }
    .add-cta-text {
        display: flex;
    }
}
</style>