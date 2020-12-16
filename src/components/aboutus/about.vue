<template >
  <div>
        <section id="about">
        <div class="container">
          <header class="section-header">
            <h3>About Us</h3>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </header>

          <div class="row about-cols">
            <div class="col-md-4 wow fadeInUp">
              <div class="about-col">
                <div class="img">
                  <img
                    src="../../assets/images/about-mission.jpg"
                    alt=""
                    class="img-fluid"
                  />
                  <div class="icon">
                <i class="fal fa-tachometer-alt"></i>
                  </div>
                </div>
                <h2 class="title"><a href="#">Our Mission</a></h2>
                <p>
                  Lorem ipsum dolor sit amet, consectetur elit, sed do eiusmod
                  tempor ut labore et dolore magna aliqua. Ut enim ad minim
                  veniam, quis nostrud exercitation ullamco laboris nisi ut
                  aliquip ex ea commodo consequat.
                </p>
              </div>
            </div>

            <div class="col-md-4 wow fadeInUp" data-wow-delay="0.1s">
              <div class="about-col">
                <div class="img">
                  <img
                    src="../../assets/images/about-plan.jpg"
                    alt=""
                    class="img-fluid"
                  />
                  <div class="icon"><i class="far fa-list-alt"></i></div>
                </div>
                <h2 class="title"><a href="#">Our Plan</a></h2>
                <p>
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem
                  doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
                  illo inventore veritatis et quasi architecto beatae vitae
                  dicta sunt explicabo.
                </p>
              </div>
            </div>

            <div class="col-md-4 wow fadeInUp" data-wow-delay="0.2s">
              <div class="about-col">
                <div class="img">
                  <img
                    src="../../assets/images/about-vision.jpg"
                    alt=""
                    class="img-fluid"
                  />
                  <div class="icon"><i class="far fa-eye"></i></div>
                </div>
                <h2 class="title"><a href="#">Our Vision</a></h2>
                <p>
                  Nemo enim ipsam voluptatem quia voluptas sit aut odit aut
                  fugit, sed quia magni dolores eos qui ratione voluptatem sequi
                  nesciunt Neque porro quisquam est, qui dolorem ipsum quia
                  dolor sit amet.
                </p>
              </div>
            </div>
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
<style>

.section-header h3 {
    font-size: 32px;
    color: #111;
    text-transform: uppercase;
    text-align: center;
    font-weight: 700;
    position: relative;
    padding-bottom: 15px;
}
.section-header h3::before {
    content: '';
    position: absolute;
    display: block;
    width: 120px;
    height: 1px;
    background: #ddd;
    bottom: 1px;
    left: calc(50% - 60px);
}
.section-header h3::after {
    content: '';
    position: absolute;
    display: block;
    width: 40px;
    height: 3px;
    background: #039ee3;
    bottom: 0;
    left: calc(50% - 20px);
}
  #about {
    background: url("../../assets/images/about-bg.jpg") center top no-repeat fixed;
    background-size: cover;
    padding: 60px 0 40px 0;
    position: relative;
}

#about::before {
    content: '';
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    background: rgba(255, 255, 255, 0.92);
    z-index: 9;
}

#about .container {
    position: relative;
    z-index: 10;
}

#about .about-col {
    background: #fff;
    border-radius: 0 0 4px 4px;
    box-shadow: 0px 2px 12px rgba(0, 0, 0, 0.08);
    margin-bottom: 20px;
}

#about .about-col .img {
    position: relative;
}

#about .about-col .img img {
    border-radius: 4px 4px 0 0;
}

#about .about-col .icon {
    width: 64px;
    height: 64px;
    padding-top: 8px;
    text-align: center;
    position: absolute;
    background-color: #039ee3;
    border-radius: 50%;
    text-align: center;
    border: 4px solid #fff;
    left: calc( 50% - 32px);
    bottom: -30px;
    transition: 0.3s;
}

#about .about-col i {
    font-size: 36px;
    line-height: 1;
    color: #fff;
    transition: 0.3s;
}

#about .about-col:hover .icon {
    background-color: #fff;
}

#about .about-col:hover i {
    color: #039ee3;
}

#about .about-col h2 {
    color: #000;
    text-align: center;
    font-weight: 700;
    font-size: 20px;
    padding: 0;
    margin: 40px 0 12px 0;
}

#about .about-col h2 a {
    color: #000;
}

#about .about-col h2 a:hover {
    color:#039ee3;
}

#about .about-col p {
    font-size: 14px;
    line-height: 24px;
    color: #333;
    margin-bottom: 0;
    padding: 0 20px 20px 20px;
}


</style>