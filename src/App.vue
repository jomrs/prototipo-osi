<template>
  <div id="app">
    <prototipo/>
  </div>
</template>

<script>
import Prototipo from './components/Prototipo.vue'

export default {
  name: 'App',
  components: {
    Prototipo
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
  margin-top: 12px;
}
.display {
  width: 2rem;
  height: 2rem;
  margin-left: 19rem;
}
.arrow {
  width: 1.5rem;
  height: 1.5rem;
  margin-left: 19.27rem;
}
.monitores {
  display: flex;
  justify-content: center;
}
</style>
