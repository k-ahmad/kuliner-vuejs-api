<template>
  <div class="d-sm-block d-md none">
    <div class="row">
      <div class="col">
        <div class="d-flex h-100">
          <div class="justify-content-center align-self-center">
            <h2>
              <strong>Delicious Food Menu,</strong> <br />
              In Your Gadget
            </h2>
            <p>Ayo segera pilih dan pesan makanan favorit Anda</p>
            <router-link class="btn btn-danger" to="/foods">
              <b-icon icon="arrow-right"></b-icon> Pesan</router-link
            >
          </div>
        </div>
      </div>
      <div class="col">
        <img src="../assets/images/hero.png" width="100%" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
</style>