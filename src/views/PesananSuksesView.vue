<template>
  <div>
    <!-- Desktop Pesanan Sukses View -->
    <NavbarView />
    <div class="d-none d-md-block">
      <div class="container">
        <div class="row justify-content-center mt-5">
          <div class="col text-center">
            <img src="../assets/images/menunggu.png" width="300" />
            <h2 class="mb-3"><strong> Sukses!! </strong></h2>
            <h4 class="mb-4">
              Pesanan anda segera diproses 😊 <br />
              Selamat menunggu❤️
            </h4>
          </div>
        </div>
      </div>
    </div>

    <!-- Mobile Pesanan Sukses View -->
    <div class="d-sm-block d-md-none">
      <div class="container">
        <div class="row justify-content-center mt-5 mb-5">
          <div class="col text-center mb-4">
            <img src="../assets/images/menunggu.png" width="300" />
            <h2 class="mb-3"><strong> Sukses!! </strong></h2>
            <h4 class="mb-4 text">
              Pesanan anda segera diproses 😊 <br />
              Selamat menunggu❤️
            </h4>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavbarView from '@/components/NavbarView.vue';
export default {
  name: 'PesananSuksesView',
  components: { NavbarView },
};
</script>

<style scoped></style>
