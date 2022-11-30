<template>
  <div id="app">
    <img src="./assets/EvanYou.jpeg" alt="Evan You" />
    <p>VueJS was founded in 2014 by Evan You, pictured above.</p>
    <HeaderComponent />
    <BodyComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from '@/components/header.vue'
import BodyComponent from '@/components/body.vue'
import FooterComponent from '@/components/footer.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    BodyComponent,
    FooterComponent,
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
  margin-top: 60px;
}

#app img {
  height: 15vh;
}
</style>
