<template>
  <div id="app">
    <HelloWorld>
      <template v-slot:title>
        <link rel="preload" href="https://f1u-cd-mst-mny-eu-ce.wsf-e-loreal.com/en/-/media/project/loreal/brand-sites/mny/master/dmi/greenedition/landingpage_headers_greenedition_1440x540_2.jpg" as="image" type="image/jpg" />
      </template>
    </HelloWorld>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
</style>
