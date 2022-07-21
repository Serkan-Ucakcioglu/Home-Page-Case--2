<script lang="ts" setup>
import HeaderBar from './components/HeaderBar.vue';
import SectionContent from './components/Section/SectionContent.vue';
import FooterBar from './components/FooterBar.vue';

</script>
<template>
  <HeaderBar/>
  <SectionContent/>
  <FooterBar/>
</template>



<style lang="scss">
.container{
  width: 90%;
  max-width: 1250px;
  margin: 0px auto;
}
a{
  text-decoration: none;
}
</style>
