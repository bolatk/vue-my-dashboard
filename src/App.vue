<template>
  <v-app>
    <NavBar/>
    <v-main class="ma-4">
      <router-view></router-view>
    </v-main>
    <Footer/>
  </v-app>
</template>

<script>
import NavBar from '@/components/NavBar'
import Footer from '@/components/Footer'

export default {
  name: 'App',
  components: {
    NavBar,
    Footer
  }
    
}
</script>