<template>
  <div class="home">
    <HeaderComp/>
     <HowItsWork/>
     <CornerSky/>
    <BeyondTheBook/>
    <OurBook/>
    <AnalyzeReader/>
    <ClaimCorner/>
    <FooterComp/>
  </div>
</template>

<script>
import HeaderComp from '@/components/Header.vue'
import HowItsWork from '@/components/HowItsWork.vue';
import CornerSky from '@/components/CornerSky.vue';
import BeyondTheBook from '@/components/BeyondTheBook.vue';
import OurBook from '@/components/OurBook.vue';
import AnalyzeReader from '@/components/AnalyzeReader.vue';
import ClaimCorner from '@/components/ClaimCorner.vue';
import FooterComp from '@/components/Footer.vue';
export default {
  name: 'HomeView',
  components:{
    HeaderComp,
    HowItsWork,
    CornerSky,
    BeyondTheBook,
    OurBook,
    AnalyzeReader,
    ClaimCorner,
    FooterComp,
}
}
</script>
