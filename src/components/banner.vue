<template>
    <div class="backImage">
        <div class="content">
            <div class="left-part">
                <h1>让卖车更透明</h1>
            </div>
            <div class="mid"></div>
            <div class="right-part">
                <ul>
                    <li>
                        <h1>3000</h1>
                    </li>
                    <li>
                        <h3>买家同时在线</h3>
                    </li>
                </ul>
                <ul>
                    <li>
                        <h1>20%</h1>
                    </li>
                    <li>
                        <h3>更高多卖</h3>
                    </li>
                </ul>
                <ul>
                    <li>
                        <h1>0费用</h1>
                    </li>
                    <li>
                        <h3>全程</h3>
                    </li>
                </ul>
            
            </div>

        </div>
        

    </div>
</template>

<script >
</script>

<style scoped>
    .backImage {
        background-image:url('~@/assets/cover-2.jpg');
        height: 20vh;
    }

    .content {
        display: flex;
        justify-content: space-around;
        font-family: 'Noto Sans HK';
    }

    .right-part li{
        list-style-type: none;
        align-items: center;
    }

    .right-part ul{
        display: inline-block;
        padding: 0 2cm;
        color: white;
    }

    .left-part {
        margin-bottom: auto;
        margin-top: auto;
        font-size: 24px;
        color: white;
    }

    
    
   
</style>