<template>
  <div>
    <h1>Welcome to our page!</h1>
    <p>Have a look around and let us know what you think!</p>

    <page-testimonials></page-testimonials>
  </div>
</template>

<script>
import PageTestimonials from "@/components/PageTestimonials.vue";

export default {
  name: "page-body",
  components: {
    PageTestimonials,
  },
};
</script>

<style scoped>
div {
  display: grid;
  place-items: center;
  grid-template-rows: 50px 34px;
}
</style>