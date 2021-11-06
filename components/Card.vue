<template>
  <div class="card w-100" style="width: 18rem">
    <div class="card-body">
      <h5 class="card-title">{{ title }}</h5>
      <p class="card-text">
        {{ body }}
      </p>
      <NuxtLink :to="`/${linkTo}`" class="btn btn-outline-light">Go »</NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    body: {
      type: String,
      required: true,
    },
    linkTo: {
      type: String,
      required: true,
    },
  },
};
</script>
