<template>
  <div id="app">
    <!--Navbar-->
    <nav class="navbar navbar-toggleable-md navbar-dark fixed-top scrolling-navbar">
        <div class="container">
            <button style ="padding-top:15px;"  class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarNav1" aria-controls="navbarNav1" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand" href="#home">
                <img class="d-inline-block align-top"  height="50" src="./assets/img/logo.png" alt="logo">
            </a>
            <div class="collapse navbar-collapse" id="navbarNav1">
                <ul class="navbar-nav mr-auto smooth-scroll" style ="padding-top:7px;">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home"><h3>Home</h3> <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about" ><h3>About</h3></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#services" ><h3>Our Services</h3></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#technology" ><h3>Technology</h3></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#team" ><h3>Team</h3></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact-us" ><h3>Contact Us</h3></a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
         <!--
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
            <a class="navbar-brand" href="#home">  <img class="d-inline-block align-top"  height="30" src="./assets/img/logo.png" alt="logo"></a>
            <button style ="padding-top:20px;" class=" navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar1" aria-controls="navbar1" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon" ></span>
            </button>

              <div class="collapse navbar-collapse" id="navbar1" >
                <ul class="navbar-nav mr-auto smooth-scroll" style ="padding-top:7px;"  role="navigation">
                    <li class="nav-item">
                      <a class="nav-link active" href="#home"><h3>Home</h3> <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about" ><h3>About</h3></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#services" ><h3>Our Services</h3></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#technology" ><h3>Technology</h3></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#team" ><h3>Team</h3></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact-us" ><h3>Contact Us</h3></a>
                    </li>
                </ul>
            </div>
    </nav> -->

    <!--/.Navbar-->
    <!--Carousel Wrapper-->
    <div id="video-carousel-example2" class="carousel slide carousel-fade" data-ride="carousel" >
        <!--Indicators-->
        <!-- <ol class="carousel-indicators">
            <li data-target="#video-carousel-example2" data-slide-to="0" class="active"></li>
            <li data-target="#video-carousel-example2" data-slide-to="1"></li>
            <li data-target="#video-carousel-example2" data-slide-to="2"></li>
        </ol> -->
        <!--/.Indicators-->

        <!--Slides-->
        <div class="carousel-inner " role="listbox" data-spy="scroll" data-target="#home" data-offset="0" >
            <!--First slide-->
            <div class="carousel-item active">
                <!--Mask color-->
                <div class="view mask pattern-5">

                    <!--Video source-->
                    <video autoplay="" loop="" class="video-full" data-wow-delay="1s" id="video-background" >
                        <source src="/static/backdropvid.mp4" type="video/mp4">Your browser does not support the video tag. I suggest you upgrade your browser.
                    </video>
                </div>

                <!--Caption-->
                <div class="carousel-caption">
                    <div class="flex-center wow animated fadeInDown" data-wow-delay="1s">
                        <ul class="smooth-scroll">
                            <li>
                                <h1 class="display-2 ">Division By Zero</h1>
                            </li>
                            <li>
                                <h1 class ="h1-responsive text-primary ">Custom Software Development for your Startup or Business</h1>
                            </li>
                            <li>
                                <h3 class = "h3-responsive text-default text-muted">Web Apps, Scripts, APIs, Mobile and Backend Software</h3>
                            </li>
                            <li >
                                <a target="_blank" href="#contact-us" class="btn btn-primary btn-lg" rel="nofollow">GET A QUOTE</a>
                                <a target="_blank" href="#services" class="btn btn-pink btn-lg" rel="nofollow">LEARN MORE</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <!--Caption-->
            </div>
            <!--/First slide-->

        </div>
        <!--/.Slides-->

        <!--Controls-->
        <!-- <a class="carousel-control-prev" href="#video-carousel-example2" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#video-carousel-example2" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a> -->
        <!--/.Controls-->
    </div>
    <!--/.Carousel Wrapper-->
    <!-- Purple Header -->
    <!--Navigation links with a Smooth SCroll effect-->


    <div class="streak flex-center py-3" style ="height:auto;">
      <div class="row">
        <div class="col-md-12 text-center">
          <h3 class="wow fadeIn" data-wow-delay="0.3s"><i class="fa fa-quote-left" aria-hidden="true"></i> Because the people who are crazy enough to think they can change the world, are the ones who do. <i class="fa fa-quote-right" aria-hidden="true"></i></h3>
          <h5 class="text-center font-italic wow fadeIn" data-wow-delay="0.2s">~ Steve Jobs</h5>
        </div>
        <div class="col-md-6">
          <ul>
          </ul>
        </div>
      </div>
    </div>

    <div class="background-light">
        <about class="col-sm-12 col-md-9 col-lg-9 mx-auto float-none" id="about"></about>
    </div>

    <div class="streak flex-center negsection py-3" style ="height:auto;">
      <div class="row container text-center">
        <div class="col-lg-3 col-sm-3 ">
           <div class="circle circle3 ">
              <a href="#section_3">
                 <h3 class = "text-white">
                    <small>30+</small>
                    <p>Years of Experience</p>
                 </h3>
              </a>
           </div>
        </div>
        <div class="col-lg-3 col-sm-3">
           <div class="circle circle2">
              <a href="#section_2">
                 <h3 class = "text-white">
                    <small>25+</small>
                    <p>Customers</p>
                 </h3>
              </a>
           </div>
        </div>
         <div class="col-lg-3 col-sm-3">
            <div class="circle circle1">
               <a href="#section_1">
                  <h3 class = "text-white">
                     <small>80+</small>
                     <p>Solutions</p>
                  </h3>
               </a>
            </div>
         </div>
         <div class="col-lg-3 col-sm-3">
            <div class="circle">
               <a href="#section_4">
                  <h3 class = "text-white">
                     <small>3000+</small>
                     <p>Cups of Coffee</p>
                  </h3>
               </a>
            </div>
         </div>
      </div>
    </div>




    <services class="col-sm-12 col-md-9 col-lg-9 mx-auto float-none"  id="services"></services>
    <div class="background-light">
        <technology class="col-sm-12 col-md-9 col-lg-9  mx-auto float-none "  id="technology"></technology>
    </div>
    <team class="col-sm-12 col-md-9 col-lg-9 mx-auto float-none"  id="team"></team>

    <!--Footer-->
    <footer class="page-footer">
        <contact-us class="col-sm-12 col-md-9 col-lg-9 mx-auto float-none"  id="contact-us"></contact-us>
        <!--Call to action-->
        <!-- <div class="call-to-action">
            <h4>Material Design for Bootstrap</h4>
            <ul class="smooth-scroll">
                <li>
                    <h5>Get our UI KIT for free</h5></li>
                <li><a target="_blank" href="http://mdbootstrap.com/getting-started/" class="btn btn-danger" rel="nofollow">Sign up!</a></li>
                <li><a target="_blank" href="http://mdbootstrap.com/material-design-for-bootstrap/" class="btn btn-default" rel="nofollow">Learn more</a></li>
            </ul>
        </div> -->
        <!--/.Call to action-->

        <!--Copyright-->
        <div class="footer-copyright">
            <div class="container-fluid">
                © 2017 Copyright: <a href="https://divisionbyzero.co.za"> divisionbyzero.co.za </a>

            </div>
        </div>
        <div class="fixed-action-btn smooth-scroll" style="bottom: 45px; right: 24px;">
          <a href="#home" class="btn-floating btn-large red">
          <i class="fa fa-arrow-up"></i>
          </a>
        </div>
        <!--/.Copyright-->

    </footer>
    <!--/.Footer-->

  </div>
</template>

<script>
import About from './components/About'
import Services from './components/Services'
import Technology from './components/Technology'
import Team from './components/Team'
import ContactUs from './components/ContactUs'
export default {
  name: 'app',
  components: {
    About,
    Services,
    Technology,
    Team,
    ContactUs
  }
}
</script>
<style>
</style>
