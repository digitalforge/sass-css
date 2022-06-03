<template>
  <Header />
  <main>
    <About />
    <Features />
    <Tours />
    <Stories />
  </main>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header"
import About from "@/components/About"
import Features from "@/components/Features"
import Tours from "@/components/Tours"
import Stories from "@/components/Stories"

export default {
  components: { Header, About, Features, Tours, Stories },
  setup() {},
}
</script>
