<template class="dark">
  <div style="margin-top: 40px">
    <side-menu id="side-menu"></side-menu>
    <div class="home">
<!--      <carousel id="carousel"></carousel>-->
<!--      <update-card id="update-card"></update-card>-->
<!--      <slogan id="slogan"></slogan>-->

    </div>
  </div>
</template>

<script>
// import Carousel from './Carousel'
// import QuickNav from './QuickNav'
// import Slogan from './Slogan'
// import About from '@/components/common/About'
// import UpdateCard from './UpdateCard'
import SideMenu from './SideMenu'
export default {
  name: 'AppIndex',
  components: {SideMenu}
}
</script>

<style scoped>
.home {
  width: 990px;
  margin-left: auto;
  margin-right: auto;
  margin-top: -20px;
}

/*#header-div {*/
/*  !*padding-bottom: 20px;*!*/
/*  !*padding-left: 5px;*!*/
/*  background-color: white;*/
/*}*/

#side-menu {
  position: fixed;
  margin-left: 50%;
  left: -680px;
  top: 100px;
}

* {
  margin: 0;
  padding: 0;
  font-family: '微软雅黑', Arial, Helvetica, sans-serif;
}

body {
  font-size: 12px;
}

div {
  font-size: 12px;
}

span {
  font-size: 12px;
}

.footer {
  background: #2b2e33;
}

.footer .alt {
  overflow: hidden;
  padding: 20px 0;
  width: 1160px;
  margin: auto;
}

.footer .alt .foot {
  width: 138px;
  float: left;
}

.footer .alt .foot p {
  color: #FFF;
  line-height: 28px;
}

a{
  text-decoration: none;
}

.footer .alt .foot a {
  color: #999;
  display: block;
  line-height: 24px;
}
</style>