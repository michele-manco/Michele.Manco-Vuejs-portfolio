<template>
  <div id="app">
    <navigation/>
    <!-- //using the navigation component in the template section -->
    <router-view></router-view>
    <Footer/>
    </div>
</template>
<script>
import Navigation from './components/includes/navigation.vue' //import the component
import Footer from './components/includes/footer.vue'


export default {
  name: 'App',
  components: {
    Navigation,
    Footer
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
  background-color:lavender;
}

</style>
