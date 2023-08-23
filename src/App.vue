<template>
  <div id="app">
    <router-view />
    <Footer></Footer>
  </div>
</template>

<script>
import Footer from "@/components/FooterPage.vue";
export default {
  components: {
    Footer,
  },
};
</script>
<style></style>
