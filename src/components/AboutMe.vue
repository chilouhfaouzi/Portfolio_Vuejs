<template>
  <div class="about-me">
    <div class="about-image">
      <img src="../assets/images/focalimg.png" />
    </div>
    <div class="about-info">
      <h2>About Me</h2>
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iste natus,
        voluptas adipisci delectus ad excepturi ipsa! Quia, molestiae mollitia
        veritatis est veniam possimus, eveniet rerum sint, omnis velit ipsa
        illo.
      </p>

      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nihil quo
        cumque ipsam vel repudiandae quos neque, expedita, quia deserunt
        assumenda esse hic sed porro.
      </p>
      <div class="about-competence">
        <div class="web web-design">
          <div class="clearfix"></div>
          <div class="icon-web"></div>
          <div class="web-info">
            <h3>web design</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit
              deleniti.
            </p>
          </div>
        </div>
        <div class="web graphic-design">
          <div class="clearfix"></div>
          <div class="icon-graphic"></div>
          <div class="web-info">
            <h3>graphic design</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit
              deleniti.
            </p>
          </div>
        </div>
        <div class="web online-marketing">
          <div class="clearfix"></div>
          <div class="icon-online"></div>
          <div class="web-info">
            <h3>online marketing</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit
              deleniti.
            </p>
          </div>
        </div>
        <div class="web seo">
          <div class="clearfix"></div>
          <div class="icon-seo"></div>
          <div class="web-info">
            <h3>seo</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit
              deleniti.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "About-Me",
};
</script>

<style scoped>
.about-me {
  background-color: #f2f2f2;
  overflow: hidden;
  padding-right: 5px;
}
.about-image {
  float: left;
  width: 35%;
  height: 600px;
}

.about-image img {
  width: 100%;
  height: 750px;
}
.about-info {
  float: left;
  width: 65%;
  padding: 60px;
  padding-left: 50px;
  padding-right: 50px;
}
.about-info h2 {
  color: #434343;
}
.about-info p {
  margin-top: 25px;
}
.about-competence {
  margin: 35px 0;
  padding-bottom: 25px;
}
.about-competence .web {
  float: left;
  width: 50%;
}
.web-design .icon-web,
.graphic-design .icon-graphic,
.online-marketing .icon-online,
.seo .icon-seo {
  float: left;
  width: 12%;
  margin-right: 15px;
  margin-top: 40px;
}
.web-info {
  float: left;
  width: 80%;
}
.web-design .icon-web {
  content: url("../assets/images/webds.svg");
}
/*.web-design .icon-web{
    content: "\f7a2";
}*/

.graphic-design .icon-graphic {
  content: url("../assets/images/graphicds.svg");
}
.online-marketing .icon-online {
  content: url("../assets/images/online.svg");
}
.seo .icon-seo {
  content: url("../assets/images/seo.svg");
}
</style>
