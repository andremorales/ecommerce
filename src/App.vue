<template>
  <div class="phone-viewreport">
    <md-toolbar>
    <md-button class="md-icon button" v-on:click="">
      <md-icon>menu</md-icon>
    </md-button>  

      <h1 class="mb-title right">{{title}}</h1>
    </md-toolbar>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      title: "Ecommerce"
    };
  }
};
</script>

<style>
</style>
