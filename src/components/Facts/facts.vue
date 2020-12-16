<template >
  <div>
   <section id="facts" class="wow fadeIn">
        <div class="container">
          <header class="section-header">
            <h3>Facts</h3>
            <p>
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque
            </p>
          </header>

          <div class="row counters">
            <div class="col-lg-3 col-6 text-center">
              <span data-toggle="counter-up">274</span>
              <p>Clients</p>
            </div>

            <div class="col-lg-3 col-6 text-center">
              <span data-toggle="counter-up">421</span>
              <p>Projects</p>
            </div>

            <div class="col-lg-3 col-6 text-center">
              <span data-toggle="counter-up">1,364</span>
              <p>Hours Of Support</p>
            </div>

            <div class="col-lg-3 col-6 text-center">
              <span data-toggle="counter-up">18</span>
              <p>Hard Workers</p>
            </div>
          </div>

          <div class="facts-img">
            <img src="../../assets/images/screen1.png" alt="" class="img-fluid" />
          </div>
        </div>
      </section>
    
  </div>
</template>
<script>
export default {
  data() {
    return {
      
    }
  },
}
</script>
<style scoped>
  
#facts {
    background: url("../../assets/images/facts-bg.jpg") center top no-repeat fixed;
    background-size: cover;
    padding: 60px 0 0 0;
    position: relative;
}

#facts::before {
    content: '';
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    background: rgba(255, 255, 255, 0.88);
    z-index: 9;
}

#facts .container {
    position: relative;
    z-index: 10;
}

#facts .counters span {
    font-family: "Montserrat", sans-serif;
    font-weight: bold;
    font-size: 48px;
    display: block;
    color: #18d26e;
}

#facts .counters p {
    padding: 0;
    margin: 0 0 20px 0;
    font-family: "Montserrat", sans-serif;
    font-size: 14px;
    color: #111;
}

#facts .facts-img {
    text-align: center;
    padding-top: 30px;
}

</style>