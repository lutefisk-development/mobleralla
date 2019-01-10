<template>
   <div class="kitchenshelves">
      <Navbar></Navbar>
      <h1>DETTA ÄR SIDAN TILL ALLA KÖKSHYLLOR</h1>
   </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'kitchenshelves', 
  components: {
    Navbar
  }
}
</script>