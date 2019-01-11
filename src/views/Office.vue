<template>
<<<<<<< Updated upstream
   <div class="office">
      <Navbar></Navbar>
      <h1>DETTA ÄR KONTOR SIDAN</h1>
   </div>
=======
<div class="home">
    <FillWithContent picture = "https://se.sofacompany.com/media/catalog/product/cache/d13c0f82f8ebfb04d96519ed59bc94be/1/2/125603194294_astha_3seater_1760x880grey_v1.jpg"/>
	</FillWithContent>
	<FillWithContent textInformation ="massa skit"/>
	</FillWithContent>
  </div>
>>>>>>> Stashed changes
</template>

<script>
// @ is an alias to /src
<<<<<<< Updated upstream
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'office', 
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
  name: 'Office',
  components: {
    FillWithContent,
    picture,
    textInformation,
    MainFrameForInfo
  }
}


>>>>>>> Stashed changes
</script>