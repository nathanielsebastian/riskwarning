<template>
    <div>
      <header-component></header-component>
      <container-component></container-component>
    </div>
  </template>
  
  <script>
  import HeaderComponent from '../components/header.vue';
  import ContainerComponent from '../components/container.vue';
  
  export default {
    components: {
      'header-component': HeaderComponent,
      'container-component': ContainerComponent
    }
  }
  </script>
  
  