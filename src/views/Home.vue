<template>
  <div>
    <div class="lunbo">
      <div class="banner swiper-container" id="m_home_banner">
			<ul class="swiper-wrapper" id="banner">
				<li class="swiper-slide"><a href="#"><img src="../images/2.03.jpg"/></a></li>
				<li class="swiper-slide"><a href="#"><img src="../images/2.04.jpg"/></a></li>
				<li class="swiper-slide"><a href="#"><img src="../images/2.05.jpg"/></a></li>
				<li class="swiper-slide"><a href="#"><img src="../images/2.03.jpg"/></a></li>
			</ul>
			<div class="swiper-pagination banner-pagination"></div>	
	    </div>
    </div>
  </div>
</template>

<script>
	var banner=new Swiper(".banner",{
		speed:400,
		autoplay:5000,
		autoplaydisableoninteraction:false,
		loop:true,
		pagination:'.banner-pagination',
		paginationClickable:true
	 })
	</script>

<script>
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
  }
}
</script>

<style>
.lunbo{width: 90%;margin: 0 auto;}
.lunbo img{width:100%}
</style> 

