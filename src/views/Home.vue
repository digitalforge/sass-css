<template>
  <Header />
  <main>
    <About />
  </main>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header"
import About from "@/components/About"

export default {
  components: { Header, About },
  setup() {},
}
</script>
