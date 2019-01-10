<template>
   <div class="countertops">
      <Navbar></Navbar>
      <h1>DETTA ÄR SIDAN TILL ALLA BÄNKSKIVOR</h1>
   </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'countertops', 
  components: {
    Navbar
  }
}
</script>