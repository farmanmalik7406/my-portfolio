<template>
  <div id="hero" class="hero route bg-image" :style="{'background-image': 'url('+heroBG+')'}">
     <div class="overlay-itro"></div>
     <div class="hero-content display-table">
       <div class="table-cell">
         <div class="container">
           <!--<p class="display-6 color-d">Hello, world!</p>-->
           <h1 class="hero-title mb-4">I am Farman Malik</h1>
           <p class="hero-subtitle">

           <vue-typed-js :loop="true" :strings="['Designer', 'Developer','Freelancer','Photographer']">
           <span class="typed">I'm a <span class="typing"></span></span>
            </vue-typed-js>
          </p>
           <!-- <p class="pt-3"><a class="btn btn-primary btn js-scroll px-4" href="#about" role="button">Learn More</a></p> -->
         </div>
       </div>
     </div>
   </div>
 </template>

<script>
import heroBG from 'assets/img/hero-bg.jpg'
export default {
  data:()=>{
    return {
      heroBG : heroBG
    }
  }
}
</script>
