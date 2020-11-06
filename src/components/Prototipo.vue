<template>
  <div class="prototipo">

    <div>
      <b-spinner label="Loading..." v-b-tooltip.hover title="Loading...">
      </b-spinner>
    </div>

    <!-- primeira coluna -->
    <div class="d-flex flex-row container justify-content-center">

      <div class="flex-column" style="margin-right:12px;">
        <h6>Informações abaixo:</h6>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Nome da camada aqui</h5>
            <h6 class="card-subtitle mb-2 text-muted">subtitulo aqui</h6>
            <p class="card-text">exemplo de conceito que será exibido aqui.</p>
          </div>
        </div>
        <br>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Protocolos da camada atual</h5>
            <p class="card-text">exemplo aqui de protocolos que a camada contem.</p>
          </div>
        </div>
      </div>

      <div class="d-flex flex-column">
        <div class="card" style="width: 18rem;">
          <ul class="list-group list-group-flush">
            <li class="list-group-item">CAMADA 7</li>
            <li class="list-group-item">CAMADA 6</li>
            <li class="list-group-item">CAMADA 5</li>
            <li class="list-group-item">CAMADA 4</li>
            <li class="list-group-item">CAMADA 3</li>
            <li class="list-group-item">CAMADA 2</li>
            <li class="list-group-item">CAMADA 1</li>
          </ul>
        </div>
      </div>

      <div class="d-flex flex-column">
        <div class="card" style="width: 4rem;">
          <ul class="list-group list-group-flush">
            <li class="list-group-item">7</li>
            <li class="list-group-item">6</li>
            <li class="list-group-item">5</li>
            <li class="list-group-item">4</li>
            <li class="list-group-item">3</li>
            <li class="list-group-item">2</li>
            <li class="list-group-item">1</li>
          </ul>
        </div>
      </div>

      <div class="p-2 bd-highlight">d</div>

      <div class="p-2 bd-highlight">e</div>

    </div>

  </div>
</template>

<!-- script -->
<script>
export default {
}
</script>

<!-- CSS -->
<style>

</style>
