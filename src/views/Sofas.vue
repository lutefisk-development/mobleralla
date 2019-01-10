<template>
   <div class="sofas">
      <Navbar></Navbar>
      <h1>DETTA ÄR SIDAN TILL ALLA SOFFOR</h1>
   </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'sofas', 
  components: {
    Navbar
  }
}
</script>