<template>
  <div class="w-100">
    <NavBar></NavBar>
    <TextImgSection></TextImgSection>
    <InformationCom></InformationCom>
    <QuoteCom></QuoteCom>
    <sign-up></sign-up>
    <FooterCom></FooterCom>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import TextImgSection from '@/components/TextImgSection.vue';
import InformationCom from '@/components/InformationCom.vue';
import QuoteCom from '@/components/QuoteCom.vue';
import SignUp from '@/components/SignUp.vue';
import FooterCom from '@/components/FooterCom.vue'
export default {
  name: 'HomeView',
  components: {
    NavBar,
    TextImgSection,
    InformationCom,
    QuoteCom,
    SignUp,
    FooterCom
  }
}
</script> 

<style scoped>

</style>