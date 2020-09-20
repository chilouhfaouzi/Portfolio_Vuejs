<template>
  <Nav />
  <div class="clearfix"></div>
  <Features />
  <div class="clearfix"></div>
  <about-me />
  <my-skills />
  <div class="clearfix"></div>
  <Testi />
  <div class="clearfix"></div>
  <contact />
  <div class="clearfix"></div>
  <Footer />
</template>

<script>
import Nav from "./components/Nav.vue";
import Features from "./components/Features.vue";
import AboutMe from "./components/AboutMe.vue";
import MySkills from "./components/Myskills.vue";
import Testi from "./components/Testimonials.vue";
import contact from "./components/contact.vue";
import Footer from "./components/footer.vue";

export default {
  name: "App",
  components: {
    Nav,
    Features,
    AboutMe,
    MySkills,
    Testi,
    contact,
    Footer,
  },
};
</script>

<style>
#app {
  /*Start My Frame work */
}
.text-center {
  text-align: center;
}

.float-left {
  float: left;
}
.float-right {
  float: right;
}

.h1 {
  /*bach n3tiw lprppreites dyal h1 l ay header bghina*/
  font-size: 2em;
}
.clearfix {
  clear: both;
}
.resp-para {
  /*responsive-paragraph  */
  line-height: 1.8;
  font-size: 20px;
}
.list-unstyled {
  list-style: none;
  /* margin: 0;
    padding: 0; */
}
.responsive-image {
  width: 120px;
}
.img-circle {
  border-radius: 50%;
}
.img-thumbnail {
  /*Bhal l itar  */
  padding: 3px;
  background-color: #fff;
  border: 1px solid #ccc;
}
.dispaly-flex {
  display: flex;
}

/*End My Frame work */
* {
  box-sizing: border-box;
}

.container {
  width: 70%;
  margin: auto;
}

h2,
h3,
h4,
h5,
h6 {
  color: #6e6e6ef2;
}

h2,
h3,
h4,
h5,
h6 {
  font-family: "Arial Narrow Bold", sans-serif;
  text-transform: uppercase;
}
p {
  color: #434343ab;
  line-height: 1.5;
}

.padding-l-25 {
  padding-left: 25px;
}
.padding-r-25 {
  padding-right: 25px;
}
</style>
