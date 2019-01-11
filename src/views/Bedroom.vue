<template>
  <div class="bedroom">
    <Navbar></Navbar>
    <BedroomComponent></BedroomComponent>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import BedroomComponent from '@/components/BedroomComponent.vue'

export default {
  name: 'bedroom', 
  components: {
    Navbar,
    BedroomComponent
  }
}
</script>
