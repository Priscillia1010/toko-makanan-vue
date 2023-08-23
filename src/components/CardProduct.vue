<template lang="">
  <div class="card shadow card-product">
    <img :src="'/assets/image/' + product.gambar" class="card-img-top" />
    <div class="card-body">
      <h5 class="card-title">{{ product.nama }}</h5>
      <p class="card-text">Harga : Rp.{{ product.harga }}</p>
      <router-link :to="'/foods/' + product.id" class="btn btn-success"><b-icon-cart></b-icon-cart> Pesan</router-link>
    </div>
  </div>

</template>
<script>
export default {
  name: "CartProduct",
  props: ["product"],
};
</script>
<style lang=""></style>
