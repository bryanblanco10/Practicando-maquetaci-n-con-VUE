<template>
  <div id="app">
      <HeaderComponent />
      <div class="container">
        <!-- <CarritoComponent /> -->
        <ModalProduct />
      </div>
      <FooterComponent />
      <!-- admin -->
      <!-- <HeaderComponent />
      <MenuComponent />
      <ContentComponent /> -->
  </div>
</template>

<script>
import HeaderComponent from './components/layout/HeaderComponent.vue'
// import CarritoComponent from './components/layout/CarritoComponent.vue'
import FooterComponent from './components/layout/FooterComponent.vue'
import ModalProduct from './components/layout/modals-Products/ModalProduct.vue'
// admin
// import HeaderComponent from './components/admin/HeaderComponent.vue'
// import MenuComponent from './components/admin/MenuComponent.vue'
// import ContentComponent from './components/admin/ContentComponent.vue'

export default {
  name: 'App',
  components:{
    HeaderComponent,
    // CarritoComponent,
    FooterComponent,
    ModalProduct
    // admin
    // HeaderComponent,
    // MenuComponent,
    // ContentComponent
  }
};
</script>

<style>
  @import './assets/css/layout.css';
  /*admin*/
   /*@import './assets/css/styles.css';*/
</style>
