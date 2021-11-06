<template>
  <nav class="navbar navbar-expand-lg fixed-top navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="/">{{ brand }}</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbar"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbar">
        <div class="navbar-nav">
          <NuxtLink to="/" class="nav-link">Home</NuxtLink>
          <NuxtLink to="/linear-b" class="nav-link">Linear B</NuxtLink>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  props: {
    brand: {
      type: String,
      required: true,
    },
  },
};
</script>
