<template>
  <!--Start  Footer-->
  <div class="footter text-center">
    <div class="container">
      <p>COPYRIGHT 2020 FAOUZI - BUILT WITH PASSION</p>
      <ul class="list-unstyled">
        <li><img src="../assets/images/fb.svg" /></li>
        <li><img src="../assets/images/twitter.svg" /></li>
        <li><img src="../assets/images/instagram.svg" /></li>
        <li><img src="../assets/images/googleplus.svg" /></li>
        <li><img src="../assets/images/pint.svg" /></li>
        <li><img src="../assets/images/linkedin.svg" /></li>
      </ul>
    </div>
  </div>
  <!--End Footer-->
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
/*Strat  Footter */
.footter {
  background-color: #191f21;
  margin: auto;
  padding: 40px 0;
}
.footter p {
  color: #4b5456 !important;
}
.footter img {
  background-color: #5f5f5f;
  border-radius: 50%;
  padding: 4px;
  width: 25px;
  height: 25px;
}
.footter ul li {
  display: inline-block;
  margin-right: 5px;
}
/* End Footter */
</style>
