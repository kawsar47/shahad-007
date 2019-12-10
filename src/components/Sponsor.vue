<template>
      <div class="brand-area pt-140 ">
      <div class="container">
        <div class="row">
          <div class="brand-active owl-carousel">
            <div class="single-brand">
              <a href="#"> <img src="https://media.licdn.com/dms/image/C5122AQF6aIL5IYtZrw/feedshare-shrink_2048_1536/0?e=1579132800&v=beta&t=0xNgaULTrlwjWfAhcPC0lQrz9nKjAWqaVhBZ_XaUo1U"></a>

            </div>

            <div class="single-brand">
                <a href="#"> <img src="https://media.licdn.com/dms/image/C5122AQF6aIL5IYtZrw/feedshare-shrink_2048_1536/0?e=1579132800&v=beta&t=0xNgaULTrlwjWfAhcPC0lQrz9nKjAWqaVhBZ_XaUo1U"></a>
  
              </div>

              <div class="single-brand">
                  <a href="#"> <img src="img/brand/brand3.png"></a>
    
                </div>

                <div class="single-brand">
                    <a href="#"> <img src="img/brand/brand4.png"></a>
      
                  </div>

                  <div class="single-brand">
                      <a href="#"> <img src="img/brand/brand5.png"></a>
        
                    </div>
                    <div class="single-brand">
                        <a href="#"> <img src="img/brand/brand6.png"></a>
          
                      </div>

          </div>

        </div>

      </div>

    </div>

</template>
<script>
export default {
    name:'Sponsor'
}


    $('.brand-active').owlCarousel({
        loop:true,  
        nav:false,
        margin:30,
        navText:['Back','Next'],
        responsive:{
            0:{
                items:2
            },
            768:{
                items:3
            },
            992:{
                items:5
            },
            1200:{
                items:6
            }
        }
    })

</script>