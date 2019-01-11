<template>
  <div class="home">
<<<<<<< Updated upstream
    <Navbar></Navbar>
    <h1>DETTA ÄR STARTSIDAN</h1>
    <homeContent></homeContent>
=======
    <HelloWorld msg="Welcome to Your Vue.js App"/>
>>>>>>> Stashed changes
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

import homeContent from '@/components/home-content.vue'
import HelloWorld from '@/components/HelloWorld.vue'
export default {
  name: 'home', 
  components: {
    Navbar,
    homeContent
  }
}
</script>


<!--<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>
-->

