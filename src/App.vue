<template>
  <div id="app">
    <prototipo/>
    <footer class="rodape">
      <span>Protótipo de simulador da camada OSI - Criado por: Jonhtan Mota.</span>
    </footer>
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
  display: flex;
  justify-content: center;
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
.prototipo {
  min-height: 32rem;
  padding: 13px;
  margin: 7px;
  background: #fbfbfb;
  border: solid 1px #d4d4d4;
  border-radius: 5px;
}
.rodape {
  bottom: 0;
  left: 0;
  position: fixed;
  width: 100%;
  background: #fbfbfb;
  border: solid 1px #d4d4d4;
  color: #777;
}
</style>
