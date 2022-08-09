<template>
  <div id="app">
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>
import PageHeader from "@/components/PageHeader.vue";
import PageBody from "@/components/PageBody.vue";
import PageFooter from "@/components/PageFooter.vue";

export default {
  components: {
    PageHeader,
    PageBody,
    PageFooter,
  },
};
</script>

<style>
#app {
  display: grid;

  grid-template-rows: 100px auto 50px;
  min-height: 100vh;
}
</style>
