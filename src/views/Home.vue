<template>
  <Nav />
  <Header />
  <main>
    <About />
    <Features />
    <Tours />
    <Stories />
    <Booking />
    <Footer />
    <Popup />
  </main>
</template>

<script>
// @ is an alias to /src
import Nav from "@/components/Nav"
import Header from "@/components/Header"
import About from "@/components/About"
import Features from "@/components/Features"
import Tours from "@/components/Tours"
import Stories from "@/components/Stories"
import Booking from "@/components/Booking"
import Footer from "@/components/Footer"
import Popup from "@/components/Popup"

export default {
  components: {
    Nav,
    Header,
    About,
    Features,
    Tours,
    Stories,
    Booking,
    Footer,
    Popup,
  },
  setup() {},
}
</script>
