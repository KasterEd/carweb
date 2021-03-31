<template>
    <div class="footer">
        <div class="left-part">
            <h1>优选之车</h1>
        </div>
        <div class="right-part">
            <ul>
                <span>关于我们</span>
                <li>我要买车</li>
                <li>联系我们</li>
            </ul>
            <ul>
                <span>服务指南</span>
                <li>售后服务</li>
                <li>质保服务说明</li>
            </ul>
            <ul>
                <span>公司地址</span>
                <li>XXX省XXX市</li>
            </ul>
            
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

    .footer{
        background-color:#000000;
        height: 10vh;
        display: flex;
        justify-content: space-around;
        opacity: 70%;
    }
    .right-part{
        display: flex;
    }
    .right-part ul{
        list-style-type: none;
        flex-direction: row;
    }
    .right-part span{
        font-size: 24px;
        align-items: center;
        color: white;

    }
    .right-part li{
        text-align: center;
        font-weight: 400px;
        font-size: 16px;
        color: white;
    }

    .left-part{
        font-size: 24px;
        justify-content: center;
    }

    .left-part h1{
        margin-bottom: 2px;
        color: white;
    }
</style>