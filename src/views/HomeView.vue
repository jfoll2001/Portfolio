<script>
import Navbar from '@/components/Navbar.vue'
import Header from '@/components/Header.vue'
import Portfolio from '@/components/Portfolio.vue'
import About from '@/components/About.vue'
import Contact from '@/components/Contact.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    Navbar,
    Header,
    Portfolio,
    About,
    Contact,
    Footer
  }
}
</script>

<template>

  <body id="page-top">
    <!-- Navagation -->
    <Navbar />

    <!-- Masthead-->
    <Header />

    <!-- Portfolio Section-->
    <Portfolio />

    <!-- About Section-->
    <About />

    <!-- Contact Section-->
    <Contact />

    <!-- Footer-->
    <Footer />
  </body>

</template>
