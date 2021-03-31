<template>
  <div id="home">
    <HeaderBar />
    <latestDeal />
    <banner />
    <ourService />
    <myFooter />
    <Sidebar />
  </div>
</template>

<script>
import HeaderBar from '@/components/HeaderBar'
import latestDeal from '@/components/latestDeal'
import banner from '@/components/banner'
import ourService from '@/components/ourService'
import myFooter from '@/components/myFooter'
import Sidebar from '../components/sidebar.vue'
export default {
  name: 'Home',
  components: {
    HeaderBar,
    latestDeal,
    banner,
    ourService,
    myFooter,
    Sidebar
  }
}
</script>
<style scoped>
  @import url('https://css.gg/user.css');   
  @import url('https://css.gg/shopping-cart.css');

</style>
