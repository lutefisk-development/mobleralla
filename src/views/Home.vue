<template>
  <div class="home">
    <Navbar></Navbar>
    <h1>DETTA ÄR STARTSIDAN</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'home', 
  components: {
    Navbar
  }
}
</script>
