<template>
  <div class="phone-viewreport">
    <md-toolbar>
    <md-button class="md-icon button">

  </md-button>  
      <h1 class="mb-title">{{title}}</h1>
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
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
