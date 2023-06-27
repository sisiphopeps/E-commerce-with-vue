<template>
  <div class="home">
    <NavbarComp/>
    <router-view/>
    <FooterComp/>
  
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarComp from "../components/NavbarComp.vue"
import FooterComp from "../components/FooterComp.vue"
export default {
  name: 'HomeView',
  components: {
    NavbarComp, FooterComp
  }
}
</script>
