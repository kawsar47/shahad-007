<template>
  <div class="container">
        <carousel :items="1">

                  <div class="single-slider" style="background-image:url(./static/assets/img/slider/slider1.jpg)"> 
                        <div class="slider-text">
                          <h2>Cherner <span>Armchair</span></h2>
                          <p>The 1958 moulded plywood armchair by Norman Cherner.</p>
                          <a href="#">View now</a>

                        </div>

                      </div>

              
                            <div class="single-slider" style="background-image:url(./static/assets/img/slider/slider2.jpg)"> 
                              <div class="slider-text">
                                <h2>Cherner <span>Armchair</span></h2>
                                <p>The 1958 moulded plywood armchair by Norman Cherner.</p>
                                <a href="#">View now</a>

                              </div>

                            </div>
                    
                                  <div class="single-slider" style="background-image:url(./static/assets/img/slider/slider3.jpg)"> 
                                    <div class="slider-text">
                                      <h2>Cherner <span>Armchair</span></h2>
                                      <p>The 1958 moulded plywood armchair by Norman Cherner.</p>
                                      <a href="#">View now</a>

                                    </div>

                                  </div>
                    

        </carousel>
  </div>
</template>

<script>

   
  import carousel from 'vue-owl-carousel'
	export default {
    name: 'Slider',
    components: { carousel },

  }

   
</script>
 