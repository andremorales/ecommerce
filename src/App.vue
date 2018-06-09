<template>
  <header class="phone-viewreport">
    <md-toolbar>
    <md-button class="md-icon button" v-on:click.native="toggleLeftSidenav">
      <md-icon>menu</md-icon>
    </md-button>  

      <h1 class="mb-title right">{{title}}</h1>
    </md-toolbar>

    <mb-sidenav class="md-left" ref="leftSidenav">
      <md-toolbar class="md-medium">
        <div class="md-toolbar-container">
          <h2 class="md-title">Sidenav content</h2>
        </div>
      </md-toolbar>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam laboriosam autem aliquam quis id, quasi tenetur laborum provident aliquid quisquam placeat, voluptas itaque iste dignissimos debitis reiciendis maxime sapiente beatae.
        </p>
    </mb-sidenav>
  </header>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      title: "Ecommerce"
    };
  },
  methods: {}
};
</script>

<style>
</style>
