<template>
  <div class="home">
      <Header/>
      <Slider/>
      <ProdukSlider/>
      <InstagramPhotos/>
      <PartnerLogos/>
      <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header';
import Slider from '@/components/Slider'
import ProdukSlider from '@/components/ProdukSlider'
import InstagramPhotos from '@/components/InstagramPhotos'
import PartnerLogos from '@/components/PartnerLogos'
import Footer from '@/components/Footer'
export default {
  name: 'Home',
  components : {
      Header,Slider,ProdukSlider,InstagramPhotos,PartnerLogos,Footer
  }
}
</script>
