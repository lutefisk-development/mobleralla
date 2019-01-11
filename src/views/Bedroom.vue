<template>
<<<<<<< Updated upstream
  <div class="bedroom">
    <Navbar></Navbar>
    <BedroomComponent></BedroomComponent>
=======
<div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <FillWithContent picture = "https://se.sofacompany.com/media/catalog/product/cache/d13c0f82f8ebfb04d96519ed59bc94be/1/2/125603194294_astha_3seater_1760x880grey_v1.jpg"/>
	</FillWithContent>
	<FillWithContent textInformation ="massa skit"/>
	</FillWithContent>
>>>>>>> Stashed changes
  </div>
</template>

<script>
// @ is an alias to /src
<<<<<<< Updated upstream
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
=======
import FillWithContent from '@/components/FillWithContent.vue'
import picture from '@/components/FillWithContent.vue'
import textInformation from '@/components/FillWithContent.vue'
import MainFrameForInfo from '@/components/FillWithContent.vue'

export default {
  name: 'Bedroom',
  components: {
    FillWithContent,
    picture,
    textInformation,
    MainFrameForInfo
  }
}


</script>
>>>>>>> Stashed changes
