<template>
  <div class="features">
    <div class="container">
      <div class="feat">
        <h3>VALUES</h3>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Deleniti
          facere labore voluptates ipsa odio, quaerat molestias, sapiente nam
          asperiores autem nobis debitis dolorem eum.
        </p>
      </div>
      <div class="feat">
        <h3>GOALS</h3>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Deleniti
          facere labore voluptates ipsa odio, quaerat molestias, sapiente nam
          asperiores autem nobis debitis dolorem eum.
        </p>
      </div>
      <div class="feat">
        <h3>HOBBIES</h3>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Deleniti
          facere labore voluptates ipsa odio, quaerat molestias, sapiente nam
          asperiores autem nobis debitis dolorem eum.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Features",
};
</script>

<style scoped>
.features {
  overflow: hidden;
}
.feat {
  float: left;
  width: 32%;
  margin: 60px 0;
}

.feat p {
  line-height: 1.5;
  padding-right: 5px;
}
.feat:not(:first-of-type) {
  margin-left: 2%;
}
</style>
