<template>
    <div class="deals">
        <h1>Latest deal</h1>
        <h3>近期成交</h3>
        <ul>
            <li>
                <img src="~@/assets/car-1.jpg" >
                <h4>别克小轿车手自一体 经典版</h4>
                <div class="detail">
                    <div class="price"><h4>￥ 1230</h4></div>
                    <button class="cart"><i class="gg-shopping-cart"></i></button>
                </div>
            </li>
            <li>
                <img src="~@/assets/car-2.jpg" >
                <h4>本田小轿车手自一体 经典版</h4>
                <div class="detail">
                    <div class="price"><h4>￥ 1230</h4></div>
                    <button class="cart"><i class="gg-shopping-cart"></i></button>
                </div>
            </li>
            <li>
                <img src="~@/assets/car-3.jpg" >
                <h4>大众商务车手自一体 经典版</h4>
                <div class="detail">
                    <div class="price"><h4>￥ 123</h4></div>
                    <button class="cart"><i class="gg-shopping-cart"></i></button>
                </div>
            </li>
            <li>
                <img src="~@/assets/car-4.jpg" >
                <h4>丰田商务车手自一体 经典版</h4>
                <div class="detail">
                    <div class="price"><h4>￥ 1230</h4></div>
                    <button class="cart"><i class="gg-shopping-cart"></i></button>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>

</script>

<style scoped>
@import url('https://css.gg/shopping-cart.css');

    ul {
        display: flex;
        list-style-type: none;
        font-family: '';
    }

    li {
        height: 40vh;
        padding: 1cm;
    }

    img {
        
        max-height: 70%;
        min-width: 70%;
        object-fit: cover;
        vertical-align: left;
    }

    .deals  {
        
        background-color: white;
        width: 100%;
        
    }

    .deals h1{
        font-size: 24px;
        color:rgb(24, 23, 23);
        font-family: "Noto Sans HK";
        padding: 0 2cm;
    }

    .deals h3{
        padding: 0 2cm;
        font-size: 18px;
        color: rgb(27, 27, 27);
        font-family: "Noto Sans HK";

    }

    .deals h4{
        text-align: center;
    }

    .detail{
        display: flexbox;
        flex-direction: row;
    }


</style>