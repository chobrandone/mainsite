<template >
  <div class="major">
  <div class="header">
  <section class="head"> <Head/></section>
  <div></div>
   <section class="navi">    <Navbar/></section>
   </div>
   <section class="slider"> <Slider/> </section>
   <section> <About/>  </section>
   <section> <chooseus/> </section>
   <section> <Facts/> </section>
<section> <Contact/> </section>
   <section> <Footer/> </section>

  </div>
</template>
<script>
import Head from '../head/header';
import Navbar from '../head/navbar';
import Slider from '../slider/slider';
import chooseus from '@/components/chooseUsComponent/chooseus';
import Footer from '../footer/footer';
import Contact from '../contactus/contactus';
import About from '../aboutus/about';
import Facts from '../Facts/facts'
export default {
  data() {
    return {
      
    }
  },
  components:{
    Head,
    Navbar,
    Slider,
    chooseus,
    Footer,
    Contact,
    About,
    Facts
  }
}
</script>

<style scoped>
.major{
  overflow: hidden;
}

</style>