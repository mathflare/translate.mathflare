<template>
  <div>
    <h1 class="display-4 fw-normal">{{ text }}</h1>
    <hr class="my-4" />
  </div>
</template>

<script>
export default {
  props: {
    text: {
      type: String,
      required: true,
    },
  },
};
</script>
