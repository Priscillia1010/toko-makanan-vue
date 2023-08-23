<template lang="">
  <div class="pesanan-sukses">
    <Navbar></Navbar>
    <div class="container">
      <div class="row justify-content-center mt-5">
        <div class="col text-center">
          <img src="../assets/image/menunggu.png" class="mb-3" style="width:200px; height:200px;"/>
          <h2><strong>Berhasil !!</strong></h2>
          <h4>
            Pesanan anda sedang diproses <br /><br /><strong
              >mohon ditunggu</strong
            >
          </h4>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import Navbar from "../components/NavbarPage.vue";
export default {
  name: "PesananSukses",
  components: {
    Navbar,
  },
};
</script>
<style lang=""></style>
