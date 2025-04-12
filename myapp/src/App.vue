<template>
  <div class="container">
    <headerComponent/>
    <div class="row col-12 my-2">
      <linksComponent/>
      <bodyComponent/>
    </div>
    <footerComponent/>
  </div>
  
</template>

<script>
import headerComponent from '@/components/headerComponent.vue';
import footerComponent from './components/footerComponent.vue';
import bodyComponent from './components/bodyComponent.vue';
import linksComponent from './components/linksComponent.vue';
export default {
  name: 'App',
  components: {
    headerComponent,
    footerComponent,
    bodyComponent,
    linksComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}
</style>
