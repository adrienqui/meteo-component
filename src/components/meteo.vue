<template>
  <div>
    <h1>Meteo Updated {{counter}}</h1>
    <button @click="counter++">Ajoute</button>
  </div>
</template>

<script>
export default {
  name:'meteo',
  data: function() {
	return {
		counter: 0
	}
   }
}
</script>
