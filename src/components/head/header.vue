<template >
  <div>
      <div class="header_top">
    <div class="container">
      <div class="row">
        <div class="col-md-8">
          <div class="full">
            <div class="topbar-left">
              <ul class="list-inline d-flex mt-3">
                <li class="pl-3"> <span class="topbar-label"><i class="fa  fa-home"></i></span> <span class="topbar-hightlight">540 Lorem Ipsum New York, AB 90218</span> </li>
                <li class="pl-3 info"> <span class="topbar-label"><i class="fas fa-envelope"></i></span> <span class="topbar-hightlight"><a href="chobrandone4@gmail.com">info@yourdomain.com</a></span> </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-md-4 right_section_header_top ">
          <div class="float-left">
            <div class="social_icon">
              <ul class="list-inline d-flex mt-3">
                <li class=""><a  href="https://www.facebook.com/" title="Facebook" target="_blank"><i class="fab fa-facebook "></i></a></li>
                <li class="pl-3"><a  href="https://plus.google.com/" title="Google+" target="_blank"><i class="fab fa-google-plus-g"></i></a></li>
                <li class="pl-3"><a href="https://twitter.com" title="Twitter" target="_blank"><i class="fab fa-twitter"></i></a></li>
                <li class="pl-3"><a  href="https://www.linkedin.com" title="LinkedIn" target="_blank"><i class="fab fa-linkedin"></i></a></li>
                <li class="pl-3"><a  href="https://www.instagram.com" title="Instagram" target="_blank"><i class="fab fa-instagram"></i></a></li>
              </ul>
            </div>
          </div>
          <div class="float-right">
            <div class="appo"> <h1><a class="btn white_btn" href="make_appointment.html">Make Appointment</a> </h1></div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>
<script>
// import css from '../../assets/css/bootstrap.min.css'
export default {
  data() {
    return {
      
    }
  },
}
</script>
<style scoped>

.header_top{
  background-color: #039ee3;
  color: aliceblue;
  position: relative;
}
.info span a{
  color: white;
}
li a{
  color: aliceblue;
}
.float-right{
  height: inherit;
  background-color: aliceblue;

}
.float-right .appo{
    color: #000;
}
.float-right :hover{
background-color: #000;
color: aliceblue;
}

@media (min-width: 240px) {
  .float-left {

  }
  .header_top{
  background-color: #039ee3;
  color: aliceblue;
  position: relative;
  margin-bottom: 20px;
}

  
  }
  
</style>