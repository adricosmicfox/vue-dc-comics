<template>
  <div id="app">
    <HeaderComponent/>
    <ContentSection/>
    <MenuSection/>
    <BigFooter/>
    <SocialSection/>
    
  </div>
</template>



<script>
import HeaderComponent from './components/HeaderComponent.vue';
import ContentSection from './components/ContentSection.vue';
import MenuSection from './components/MenuSection.vue';
import BigFooter from './components/BigFooter.vue';
import SocialSection from './components/SocialSection.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    ContentSection,
    MenuSection,
    BigFooter,
    SocialSection
}
}
</script>



<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  }
</style>
