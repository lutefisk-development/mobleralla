<template>
   <div class="cupboards">
      <Navbar></Navbar>
      <h1>DETTA ÄR SIDAN TILL ALLA SKÅPLUCKOR</h1>
   </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'cupboards', 
  components: {
    Navbar
  }
}
</script>