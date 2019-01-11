<template>
   <div class="bedroomcomponent">
      <div class="container-fluid">
         <div class="row">
            <div class="col-3">
               <h5>{{ header5 }}</h5>
               <p>{{ text }}</p>
            </div>
            <div class="col">
               <img v-bind:src="{image1}" alt="">
            </div>
            <div class="col">
               <img v-bind:src="{image2}" alt="">
            </div>
         </div>
         <div class="container-fluid second">
            <div class="row">
               <div class="col-12">
                  <h3>{{ header3 }}</h3>
               </div>
            </div>
            <div class="row">
               <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
                  <div class="carousel-inner">
                     <div class="carousel-item active">
                        <img v-bind:src="{image3}" class="d-block w-100" alt="...">
                     </div>
                     <div class="carousel-item">
                        <img v-bind:src="{image4}" class="d-block w-100" alt="...">
                     </div>
                     <div class="carousel-item">
                        <img v-bind:src="{image5}" class="d-block w-100" alt="...">
                     </div>
                  </div>
                  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                     <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                     <span class="sr-only">Previous</span>
                  </a>
                  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                     <span class="carousel-control-next-icon" aria-hidden="true"></span>
                     <span class="sr-only">Next</span>
                  </a>
               </div>
            </div>
         </div>
      </div>
   </div>
</template>

<style>
  .row {
    padding-left: 100px;
    padding-right: 100px;
  }

  .col-3, .col {
    
    height: 200px;
    margin: 0 5px 30px 5px;
    padding: 0;
  }

  .col>img {
    height: 100%;
    width: 100%;
  }

  p {
    margin: 0;
    text-align: left;
  }
  h3 {
    margin: 10px 0 10px 0;
  }

  h5 {
    margin-bottom: 0.7rem;
  }

  .second {
     margin-bottom: 50px;
  }
</style>

<script>
export default {
   name: 'BedroomComponent',
   data() {
      return {
         header5: 'Sov gott!',
         header3: 'Våra nyaste produkter!',
         text: `Vi vet betydningen av en god natt sömn. Varje möbel vi säljer ned till minsta detalj, har en uppgift. Att se till att du får den bästa sömnen, varje natt!`,
         image1: '../images/pillows-1031079_1920.jpg',
         image2: '../images/bedroom-1078890_1920.jpg',
         image3: '../images/apartment-1822409_1920.jpg',
         image4: '../images/bedroom-1807837_1920.jpg',
         image5: '../images/wall-panel-416041_1280.jpg'
      }
   }
}
</script>
