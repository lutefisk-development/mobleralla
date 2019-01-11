<template>
   <div class="desks">
      <Navbar></Navbar>
      <h1> desk </h1>
   </div>

<!-- tillägget funkar inte därför bortkommenterat -->

   <!-- <div class="desk-image">
   	<img v-bind:src="image" />
   </div> -->
   <!-- <div class="desk-text">
   	<p>{{ text }}</p>
   </div> -->
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {

	// data(){
	// 	return{
	// 		desks: [
	// 			{
	// 				desk: 'Skrivbord som ger extra utrymme',
	// 				image:'https://images.trademax.se/m%C3%B6bler-bord-skrivbord/function-plus-skrivbord-tryffelvit-95859.jpg?w=670&h=447&hash=eyJ2IjoxMDMsInQiOiJwcm9kdWN0IiwibiI6IjUwOTkyOCgxKS5qcGciLCJvX3R5cGUiOiJXRUJfU0U6cHJvZHVjdHMiLCJvX2lkIjoiODA4MDIiLCJpIjo5NTg1OX0%3D',

	// 				text: 'Det här robusta skrivbordet klarar garanterat många år av kaffedrickande och hårt arbete. Du får en generös arbetsyta och en smart lösning för att hålla kablar på plats under bordsskivan.'

	// 		}]
	// 	}
	// }
  name: 'desks', 
  components: {
    Navbar
  }
}
</script>