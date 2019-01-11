<template>
<<<<<<< Updated upstream
   <div class="kitchen">
      <Navbar></Navbar>
      <h1>DETTA ÄR KÖK SIDAN</h1>
   </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'kitchen', 
  components: {
    Navbar
  }
}
</script>
=======
  <div id='mainContent'>
		<mainFrameInfo picture = "https://se.sofacompany.com/media/catalog/product/cache/d13c0f82f8ebfb04d96519ed59bc94be/1/2/125603194294_astha_3seater_1760x880grey_v1.jpg"
		description ="shuttafrasi">	
		</mainFrameInfo>

  </div>
</template>

<script>

import mainFrameInfo from '@/components/FillWithContent.vue'


export default {
  name: 'Kitchen',
  components: {
    FillWithContent,
    picture,
    textInformation,
    MainFrameInfo
  }
}
</script>

>>>>>>> Stashed changes
