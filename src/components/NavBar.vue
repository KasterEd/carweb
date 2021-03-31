<template>
    <div id="navbar">


        <div class="header-list">

            <ul class="left part">
                <li><a href="#">二手车网站</a></li>
            </ul>
    
        
            <ul class="right-part">
                <li><a href="#">首页</a></li>
                <li><a href="~@/pages/detail.vue">所有车型</a></li>
                <li><a href="#">我要卖车</a></li>
                <li><a href="#">我要估价</a></li>
                <li><a href="#">服务网点</a></li>
            </ul>
            
        </div>  
        

    </div>
</template>

<script>
export default {
    name: 'NavBar',
}
</script>

<style scoped>


@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+HK:wght@700&display=swap');

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

#navbar {
    width: 100%;

}

.header-list {
    display: flex;
    justify-content:space-between;
    align-items: center;
    background-color: transparent;
    padding: 30px 10%;
    margin-left: 30px;  
    width: 100%;

}

li,a{
    font-family: "Noto Sans HK";
    font-weight: 700;
    font-size: 18px;
    color: #ecf0f1;
    text-decoration: none;
    list-style-type: none;

}

.right-part li{
    display: inline-block;
    padding: 0 20px;

}

.left-part li{
    padding: 0 20px;
}


.right-part li a{
    transition: all 0.3s ease 0s;
}

.right-part li a:hover{
    color: #0088a9;
}




</style>