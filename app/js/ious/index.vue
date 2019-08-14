<template lang="html">
  <div>
    <Heador/>
    <Ilider/>
    <Welfatr/>
    <Service/>
    <Footer/>
    <Navbar/>
  </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Ilider from "./islider.vue"
import Welfatr from "./welfare.vue"
import Service from "./service.vue"

export default {
    components: {
        Heador,
        Ilider,
        Welfatr,
        Service,
        Footer,
        Navbar,
    },
}
</script>

<style>

</style>
