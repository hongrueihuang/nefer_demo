<template>
<Navbar />
<Banner />
<Business />
<Service />
<Cloud />
<Tech />
<Info />
<Footer />
</template>

<script>
import Navbar from './components/layout/Navbar'
import Banner from './components/home/Banner'
import Business from './components/home/Business'
import Service from './components/home/Service'
import Cloud from './components/home/Cloud'
import Tech from './components/home/Tech'
import Info from './components/home/Info'
import Footer from './components/layout/Footer'
export default {
  components: {
    Navbar,
    Banner,
    Business,
    Service,
    Cloud,
    Tech,
    Info,
    Footer
  }
}
</script>

<style lang="scss">
@import './assets/all.scss';
</style>
