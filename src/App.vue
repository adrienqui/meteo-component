<template>
  <div id="app">
    Ajouter du code
    <meteo />
  </div>
</template>

<script>
import meteo from './components/meteo.vue'

export default {
  name: 'app',
  components: {
    meteo
  }
}
</script>
