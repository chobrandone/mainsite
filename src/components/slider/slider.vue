<template>
  <div>
  <div class="loader">
  <div class="loader__element"></div>

</div>

    <div
      id="carouselExampleIndicators"
      class="carousel slide "
      data-ride="carousel"
    >
      <ol class="carousel-indicators">
        <li
          data-target="#carouselExampleIndicators"
          data-slide-to="0"
          class="active"
        ></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
     
        <div class="carousel-item active">
         <div class="overlay"></div>
          <img
            class="d-block w-100"
            src="../../assets/images/main1.jpg"
            alt="First slide"
          />
           <div class="carousel-caption d-none d-md-block mid-text">
          
    <h1>COMPUTER SERVICES</h1>
    <p>Available on it.next</p>
  </div>
        </div>
        <div class="carousel-item ">
           <div class="overlay"></div>
          <img
            class="d-block w-100"
            src="../../assets/images/main2.jpg"
            alt="Second slide"
          />
        </div>
        <div class="carousel-item">
           <div class="overlay"></div>
          <img
            class="d-block w-100"
            src="../../assets/images/main3.jpg"
            alt="Third slide"
          />
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleIndicators"
        role="button"
        data-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleIndicators"
        role="button"
        data-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>
<script>
export default {
  name: "slider",
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped>
.mid-text{
  position: absolute;
top: 300px;




}
.mid-text h1 {
  background-color:#039ee3 ;
  width: 50%;
}
.carousel-item{

  
}



.loader {
	background-color:#2d3c7f;
	overflow: hidden;
  width: 100%;
  height: 100%;
  position: relative;
  top: 0; left: 0;
  display: flex;
  align-items: center;
  align-content: center; 
  justify-content: flex-start;  
	z-index: 100000;
}

.loader__element {
	height: 3px;
	width: 100%;
	background:white;

}

.loader__element:before {
	content: '';
	display: block;
	background-color: #039ee3;
	height: 3px;
	width: 0;
  animation: getWidth 10s ease-in infinite;
}

@keyframes getWidth {
	100% { width: 100%; }
}

.overlay {
  position: absolute;

  height: 100%;
  width: 100%;
  background-color: #2d3c7f;
  opacity: 0.7;

}
</style>
