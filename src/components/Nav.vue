<template>
  <div class="Header">
    <div class="slider">
      <div class="container">
        <div style="padding-top: 45%;">
          <h1 class="Motive">WEB & GRAPHIC DESIGNER</h1>
        </div>
        <div>
          <h4 class="learn-more">LEARN MORE</h4>
        </div>
      </div>
    </div>
    <div class="navbar">
      <div class="container">
        <h2>
          <span class="logonav">f</span>fao<span style="color: #59d559"
            >uzi</span
          >
        </h2>
        <ul class="list-unstyled">
          <li>Home</li>
          <li>About me</li>
          <li>Skills</li>
          <li>Resume</li>
          <li>Testmonials</li>
          <!--Opinions of people -->
          <li>Portfolio</li>
          <li>Contact me</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.Header .slider {
  /*   background-color: #434343;*/
  background: url("../assets/images/header.png") no-repeat;
  background-size: cover;
  height: 700px;
}
.Header h2 {
  color: white;
}
.slider .Motive {
  margin: auto;
  text-align: center;
  padding: 5px 0;
  width: 527px;
  color: white;
  border-top: 2px solid white;
  border-bottom: 2px solid white;
  font-size: 38px;
  font-family: sans-serif;
}
.slider .learn-more {
  margin: 30px auto;
  border: 2px solid white;
  color: #fff;
  width: 180px;
  padding: 5px 8px;
  text-align: center;
  cursor: pointer;
}
.Header .navbar {
  background-color: #252f31;
  color: #fff;
  overflow: hidden;
}
.Header .navbar h2 {
  float: left;
  padding-top: 5px; /*bacj=h iji f meme line dyal list */
  font-family: Verdana;
  font-weight: 500;
  font-size: 21px;
  text-transform: uppercase;
}
.logonav {
  background-color: rgb(81, 85, 85);
  padding: 4px 6px;
  margin-right: 12px;
  border-radius: 1px;
}
.Header .navbar ul {
  float: right;
  padding-left: 0;
  overflow: hidden;
}
.Header .navbar ul li {
  float: left;
  padding: 10px;
}
.Header .navbar ul li,
.Header .navbar h2 {
  cursor: pointer;
}
.Header .navbar ul li:hover,
.Header .navbar h2:hover {
  color: #2ecc71;
}
</style>
