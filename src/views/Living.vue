<template>
<<<<<<< Updated upstream
   <div class="living">
      <Navbar></Navbar>
      <h1>DETTA ÄR VARDAGSRUM SIDAN</h1>
   </div>
=======
  <div id='dynamiccontent'>
    
  </div>
>>>>>>> Stashed changes
</template>

<script>
// @ is an alias to /src
<<<<<<< Updated upstream
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'living', 
  components: {
    Navbar
  }
}
=======
import FillWithContent from '@/components/FillWithContent.vue'
import picture from '@/components/FillWithContent.vue'
import textInformation from '@/components/FillWithContent.vue'
import MainFrameForInfo from '@/components/FillWithContent.vue'

export default {
  name: 'Living',
  components: {
    FillWithContent,
    picture,
    textInformation,
    MainFrameForInfo
  }
}


>>>>>>> Stashed changes
</script>