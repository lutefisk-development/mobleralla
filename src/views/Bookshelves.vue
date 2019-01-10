<template>
   <div class="bookshelves">
      <Navbar></Navbar>
      <h1>DETTA ÄR SIDAN TILL ALLA BOKHYLLOR</h1>
   </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'bookshelves', 
  components: {
    Navbar
  }
}
</script>