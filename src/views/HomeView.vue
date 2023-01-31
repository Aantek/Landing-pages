<template>
  <div class="w-screen">
    <NavBar></NavBar>
    <TextImgSection></TextImgSection>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import TextImgSection from '@/components/TextImgSection.vue';
export default {
  name: 'HomeView',
  components: {
    NavBar,
    TextImgSection,
  }
}
</script> 

<style>

</style>