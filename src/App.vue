<template>
  <div>
    <header-component></header-component>
    <!-- Isi konten situs web Anda di sini -->
  </div>
</template>

<script>
import HeaderComponent from './views/Home.vue';

export default {
  components: {
    'header-component': HeaderComponent,
  }
}
</script>