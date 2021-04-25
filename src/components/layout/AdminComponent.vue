<template>
  <div>
      <HeaderComponent />
      <MenuComponent />
      <ContentComponent />
      <!-- <FooterComponent /> -->
  </div>
</template>

<script>
import HeaderComponent from './components/admin/HeaderComponent.vue'
import MenuComponent from './components/admin/MenuComponent.vue'
import ContentComponent from './components/admin/ContentComponent.vue'
// import FooterComponent from './components/admin/FooterComponent.vue'

export default {
  name: 'App',
  components:{
    HeaderComponent,
    MenuComponent,
    ContentComponent
    // FooterComponent
  }
};
</script>

<style>
  @import './assets/css/styles.css';
</style>
