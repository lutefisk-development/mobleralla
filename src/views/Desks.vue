<template>
   <div class="desks">
      <Navbar></Navbar>
      <h1>DETTA ÄR SIDAN TILL ALLA SKRIVBORD</h1>
   </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'desks', 
  components: {
    Navbar
  }
}
</script>