<template>
  <div class="testmonials text-center">
    <div class="container">
      <p>
        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel pariatur
        est praesentium eius voluptatum incidunt vitae excepturi assumenda
        tenetur facilis laboriosam distinctio ipsam, facere labore ut natus,
        error recusandae ."
      </p>
      <h5>Amine nafid</h5>
      <ul class="list-unstyled">
        <li></li>
        <li></li>
        <li></li>
      </ul>
    </div>
  </div>
  <div class="portfolio text-center">
    <div class="container">
      <h2>Portfolio</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse odit
        voluptates unde est molestias magnam ex vel. Temporibus iste beatae
        neque consequatur eum itaque.
      </p>
      <div class="our-work">
        <div><img src="https://place-hold.it/350/33" /></div>
        <div><img src="https://place-hold.it/350/33" /></div>
        <div><img src="https://place-hold.it/350/33" /></div>
        <div><img src="https://place-hold.it/350/33" /></div>
        <div><img src="https://place-hold.it/350/33" /></div>
        <div><img src="https://place-hold.it/350/33" /></div>
        <div><img src="https://place-hold.it/350/33" /></div>
        <div><img src="https://place-hold.it/350/33" /></div>
        <div><img src="https://place-hold.it/350/33" /></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Testi",
};
</script>
<style scoped>
/*start testimonials */
.testmonials {
  background-color: #f2f2f2;
  padding: 45px 0;
}
.testmonials ul {
  padding-left: 0;
  padding-right: 10px; /*pour bien positione au dessus de h3 */
}
.testmonials h5 {
  margin: 25px 0;
}
.testmonials li:first-of-type,
.testmonials li:not(:first-of-type) {
  width: 8px;
  height: 8px;
  border: 2px solid#2ecc71;
  border-radius: 50%;
  color: #fff;
  display: inline-block;
  margin-right: 4px;
}
.testmonials li:first-of-type,
.testmonials li:hover {
  background-color: #2ecc71;
  cursor: pointer;
}

/*End testimonials */
/*Start Portfolio */
.portfolio {
  padding: 40px 0;
}
/*End Portfolio */

/*Our Work */
.our-work {
  margin: 40px 0;
}
.our-work div {
  float: left;
  margin: 30px 1%;
  width: 31.333%;
}
.our-work div img {
  width: 95%;
  height: 200px;
}
/*End Work */
</style>
