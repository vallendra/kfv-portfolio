<template>
  <v-app>
    <v-container fluid class="blue-gradient full-view">
      <v-layout align-center justify-center column fill-height text-xs-center text-sm-center text-md-center text-lg-center>
        <v-flex>
          <logo class="logo"/>
        </v-flex>
        <v-flex>
          <div data-aos="fade-up" data-aos-anchor-placement="center-bottom" data-aos-duration="3000">
          <h4 class="display-2 font-weight-thin white--text">Kyky Farly Vallendra</h4>
          <h4 class="subheading font-weight-thin white--text">Programmer, Designer, and A Great Dreamer</h4>
        </div>
        </v-flex>
        <v-flex>
          <div class="chevron"></div>
          <span class="text">Scroll down</span>
        </v-flex>
      </v-layout>
    </v-container>
    <v-container>
      <div data-aos="fade-up" data-aos-duration="2000">
        <v-layout align-center justify-center column fill-height sm12>
          <h1 class="display-3 font-weight-thin margin-all">Portfolios</h1>
       </v-layout>
      </div>
    </v-container>
    <v-container>
      <v-layout row wrap align-end justify-space-around>
          <v-flex  sm12 lg7 overflow-x-hidden order-lg2 text-xs-center text-sm-center text-md-center text-lg-left>
            <div data-aos="fade-down" data-aos-duration="2000">
            <img src="@/assets/gokil.png" width="650px">
            </div>
          </v-flex>
          <v-flex sm12 lg5 text-xs-center text-sm-center text-md-center text-lg-left>
            <div data-aos="fade-right" data-aos-duration="2000">
              <h1 class="display-3 font-weight-light">GO-KIL</h1>
              <h4 class="subheading font-weight-light">2018 - ongoing</h4><br>
              <p class="body-1">
                GO-KIL is a ride-sharing application. This application is made for final project at BNCC X GO-JEK Workshop.
              </p>
              <h4>Role: UI/UX Designer, Frontend Developer</h4>
              <v-flex>
                <v-btn color="primary" href="https://github.com/vallendra/gokil-front-3"><v-icon left>fab fa-github</v-icon>Check on Github</v-btn>
                <v-btn color="primary" href="http://gokil-kyky2.herokuapp.com/"><v-icon left>fas fa-project-diagram</v-icon>Check on Heroku</v-btn>
              </v-flex>
            </div>
          </v-flex>
      </v-layout>
    </v-container>
    <v-container>
      <v-layout row wrap align-end justify-space-around>
        <v-flex  sm12 lg4 align-center justify-center overflow-hidden text-xs-center text-sm-center text-md-center text-lg-left>
          <div data-aos="fade-down" data-aos-duration="2000">
            <img src="@/assets/darurat.png" width="350px">
          </div>
        </v-flex>
          <v-flex sm12 lg5 text-xs-center text-sm-center text-md-center text-lg-left>
            <div data-aos="fade-right" data-aos-duration="2000">
                <h1 class="display-3 font-weight-light">DARURAT!</h1>
                <h4 class="subheading font-weight-light">2018 - ongoing</h4><br>
                <p class="body-1">
                  Darurat! is an application for emergency situation. This application is made for competition at Technofest UMN 2018.
                </p>
                <h4>Role: Idea generation, UX Designer</h4>
                <v-btn color="primary" href="https://drive.google.com/open?id=1ff0D0qO11PtQfC5-kSDu1IsvcBCuzYnS"><v-icon left>fab fa-google-drive</v-icon>Check on Drive</v-btn>
              </div>
          </v-flex>
      </v-layout>
    </v-container>
    <v-container>
      <v-layout row wrap align-end justify-space-around>
          <v-flex  sm12 lg7 overflow-x-hidden order-lg2 text-xs-center text-sm-center text-md-center text-lg-left>
          <div data-aos="fade-down" data-aos-duration="2000">
            <img src="@/assets/musiqu.png" width="650px">
          </div>
          </v-flex>
          <v-flex sm12 lg5 text-xs-center text-sm-center text-md-center text-lg-left>
            <div data-aos="fade-right" data-aos-duration="2000">
              <h1 class="display-3 font-weight-light">MusiQu</h1>
              <h4 class="subheading font-weight-light">2018 - ongoing</h4><br>
              <p class="body-1">
                MusiQu is a social media and job-portal application. This project is made for Entrepreneurship Class at Binus University.
              </p>
              <h4>Role: Idea generation, UI/UX Designer</h4>
              <v-flex>
                <v-btn color="primary" href="https://xd.adobe.com/view/d0cb792e-51ad-4b0e-6eeb-4568b643e4c8-a6fa/"><v-icon left>fas fa-project-diagram</v-icon>Check the prototype</v-btn>
              </v-flex>
            </div>
          </v-flex>
      </v-layout>
    </v-container>
    <v-container class="blue-gradient" fluid>
      <div data-aos="fade-down" data-aos-duration="2000">
        <v-layout light align-center justify-center column fill-height sm12>
          <h1 class="display-3 font-weight-thin white--text margin-all">For more..</h1>
       </v-layout>
      </div>
      <v-layout>
        <v-flex xs12 text-xs-center>
          <div data-aos="fade-right" data-aos-duration="2000">
            <v-btn class="white--text" flat large href="https://github.com/vallendra"><v-icon left>fab fa-github</v-icon>Check my Github account</v-btn>
            <v-btn class="white--text" flat large href="https://bit.ly/KykyArtworks"><v-icon left>fab fa-google-drive</v-icon>Check my other artworks</v-btn>
            <v-btn class="white--text" flat large href="https://www.linkedin.com/in/kfvallendra"><v-icon left>fab fa-linkedin-in</v-icon>Connect to my Linkedin</v-btn>
          </div>
        </v-flex>
      </v-layout>
    </v-container>
    <v-footer class="pa-3 blue darken-4">
      <v-spacer></v-spacer>
        <v-flex text-xs-center white--text xs12>
          &copy; {{ new Date().getFullYear() }} Kyky Farly Vallendra, kfv.bio
        </v-flex>
    </v-footer>
  </v-app>
</template>

<script>
import Logo from './components/Logo'

export default {
  name: 'App',
  components: {
    Logo
  }
}
</script>

<style>
.logo {
  margin: 25px;
}
.margin-all {
  margin: 5%;
}

.full-view {
  height: 100vh;
}

.blue-gradient {
  background: #00b4db;
  background: -webkit-linear-gradient(to right, #00b4db, #0083b0);
  background: linear-gradient(to right, #00b4db, #0083b0);
}

.rounded-card{
    border-radius:25px;
}

.transparent {
   background-color: white!important;
   opacity: 0.65;
   border-color: transparent!important;
 }

 .chevron {
  position: absolute;
  width: 28px;
  height: 8px;
  opacity: 0;
  transform: scale3d(0.5, 0.5, 0.5);
  animation: move 3s ease-out infinite;
}

.chevron:first-child {
  animation: move 3s ease-out 1s infinite;
}

.chevron:nth-child(2) {
  animation: move 3s ease-out 2s infinite;
}

.chevron:before,
.chevron:after {
  content: ' ';
  position: absolute;
  top: 0;
  height: 100%;
  width: 51%;
  background: #fff;
}

.chevron:before {
  left: 0;
  transform: skew(0deg, 30deg);
}

.chevron:after {
  right: 0;
  width: 50%;
  transform: skew(0deg, -30deg);
}

@keyframes move {
  25% {
    opacity: 1;

  }
  33% {
    opacity: 1;
    transform: translateY(30px);
  }
  67% {
    opacity: 1;
    transform: translateY(40px);
  }
  100% {
    opacity: 0;
    transform: translateY(55px) scale3d(0.5, 0.5, 0.5);
  }
}

.text {
  display: block;
  margin-top: 75px;
  margin-left: -30px;
  font-family: "Helvetica Neue", "Helvetica", Arial, sans-serif;
  font-size: 12px;
  color: #fff;
  text-transform: uppercase;
  white-space: nowrap;
  opacity: .25;
  animation: pulse 2s linear alternate infinite;
}

@keyframes pulse {
  to {
    opacity: 1;
  }
}

</style>
