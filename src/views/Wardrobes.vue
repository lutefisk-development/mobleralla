<template>
   <div class="wardrobes">
      <Navbar></Navbar>
      <h1>DETTA ÄR SIDAN TILL ALLA GARDROBER</h1>
   </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'wardrobes', 
  components: {
    Navbar
  }
}
</script>