<template>
  <div class="container">
    <h1 class="display-4 fw-normal text-center">
      MathFlare <span class="text-success">Translate</span>
    </h1>
    <hr class="my-4" />
    <h4 class="mb-3">Popular:</h4>
    <Card
      title="Latin to Linear B"
      body="translate latin to linear-b"
      linkTo="linear-b"
    />
  </div>
</template>

<style>
html {
  height: 100vh !important;
}
body {
  background-image: url("@/assets/images/globe.svg");
  background-repeat: no-repeat;
  background-position: bottom right;
  background-size: 40em;
}
</style>

<script>
export default {
  name: "Index",
};
</script>
