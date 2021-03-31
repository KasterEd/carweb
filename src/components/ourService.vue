<template>
    <div class="service-content">
        <div class="top-items">
            <h1>OURS  SERVICE</h1>
            <h5>我们的服务</h5>

        </div>
        <div class="bottom-items">

            <ul>
                <img src="~@/assets/icon-1.webp" alt="">
                <li>高效卖车，足不出户</li>
                <li>1天结拍，当天完成交易 为您节省不必要的比价时间</li>
            </ul>
            <ul>
                <img src="~@/assets/icon-2.webp" alt="">
                <li>价比千家，省时省心</li>
                <li>超多3000专业买家在线 实时出价竞拍，不赚差价</li>
            </ul>
            <ul>
                <img src="~@/assets/icon-3.webp" alt="">
                <li>安全保障，急速打款</li>
                <li>通过诚信体系保障资金安全 签约后极速打款，实时到账</li>
            </ul>
            <ul>
                <img src="~@/assets/icon-4.webp" alt="">
                <li>全程免费，优质服务</li>
                <li>代办所有手续，全程0费用让您享受一站式贴心服务</li>
            </ul>
        </div>

    </div>
</template>

<script>
export default {
    name: 'ourService'
}
</script>

<style scope>
.bottom-items{
    display:flex;  
    justify-content: space-between;
    padding: 2px 0;
    
}

.bottom-items ul{
    flex-direction: column;
    text-align: center;
    list-style-type: none;

}

img {
        
        object-fit: cover;
        vertical-align: left;
    }


.top-items{
    padding: 0 2px;
}
.top-items h1{
    font-family: 'Noto Sans HK';
    font-weight: 500;
    margin-left: 5%;
}

.top-items h5{
    font-family: 'Noto Sans HK';
    font-weight: 300;
    margin-left: 5%;
}

.bottom-items li{
    font-family: 'Noto Sans HK';
}

</style>
