<template>
  <div id="app">
    <!-- Image and text -->
    <b-navbar variant="primary" type="light">
      <b-navbar-brand href="#">
        <img src="https://placekitten.com/g/30/30" class="d-inline-block align-top" alt="Kitten" />
        BootstrapVue
      </b-navbar-brand>
    </b-navbar>
     
   
    <router-view />  
    <!-- <todo-list />-->
    
  </div>
</template>

<script>


export default {
  name: "app",
  components: {
 
  
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
  /* margin-top: 60px;*/
}
</style>
