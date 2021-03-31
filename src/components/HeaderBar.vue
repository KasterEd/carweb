<template>
    <div id="header">
        <NavBar />

        <div class="title">
            
            <h1>优选之车</h1>
            <h3>多买20% ● 速度交易 ● 办理手续 ● 全程跟踪</h3>
            <div class="search">
                <input type="text" class="search-input" placeholder="请输入您想要搜索的品牌、车型">
                <button class="search-butt">搜索</button>
            </div>

        </div>
    </div>
    
</template>

<script>
import NavBar from '@/components/NavBar'
export default {
    name: 'HeaderBar',
    components: {
        NavBar
    }
}
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+HK:wght@700&display=swap');


#header {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 70vh;
    width: 100%;
    background-image: url('~@/assets/cover-1.jpg');
    background-repeat: repeat-;
}

.title{
    flex-direction: column;
    margin-top: auto;
    margin-bottom: auto;
    
}

.title h1{
    color:white;
    font-size: 80px;
    text-align: center;
}

.title h3{
    color: white;
    font-size: 20px;
    text-align: center;
}

.search {
    display: flex;
    width: 100%;
    background-color: white;
    padding: 0.8rem;
    border-radius: 6px;
    
}

.search-input{
    padding: 1 rem;
    border: 0;
    border-radius: inherit;
    flex-grow: 1;
    font-size:  1.4rem;
    font-family: "Noto Sans HK";
}

.search-butt {
    padding: 0.1 rem 0.1 rem;
    cursor: pointer;
    display: inline-block;
    text-align: center;
    color: white;
    background-color: #2979ff;
    border: 0;
    border-radius: inherit;
    font-size: 1.6rem;
    width: max-content;
    flex-shrink: 0;
}

</style>
