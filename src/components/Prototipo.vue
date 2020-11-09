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
        <div class="d-flex" style="width:18rem; margin:">
        <button type="button" class="btn btn-primary" v-on:click='animarPassar'>Start</button>
      </div>
      </div>

      <div class="d-flex flex-column">
        <div class="card" style="width: 8rem;">
          <ul class="list-group list-group-flush"  id="primeiraCol">
            <li class="list-group-item d-flex flex-row">
              <div class="boxp roxo"> <span id="hide">a</span> </div> 
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp lima"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp amarelo"> </div>
              <div class="boxp lima"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp laranja"> </div>
              <div class="boxp amarelo"> </div>
              <div class="boxp lima"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp vermelho"> </div>
              <div class="boxp laranja"> </div>
              <div class="boxp amarelo"> </div>
              <div class="boxp lima"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
          </ul>
        </div>
      </div>

      <div class="d-flex flex-column">
        <div class="card" style="width: 12rem;">
          <ul class="list-group list-group-flush">
            <li class="list-group-item">Aplicação</li>
            <li class="list-group-item">Apresentação</li>
            <li class="list-group-item">Sessão</li>
            <li class="list-group-item">Transporte</li>
            <li class="list-group-item">Rede</li>
            <li class="list-group-item">Enlace</li>
            <li class="list-group-item">Fisica</li>
          </ul>
        </div>
      </div>

      <div class="d-flex flex-column">
        <div style="width: 4rem;">
          <ul class="list-group">
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

      <div class="d-flex flex-column">
        <div class="card" style="width: 12rem;">
          <ul class="list-group list-group-flush" id="segundaCol">
            <li class="list-group-item">Aplicação</li>
            <li class="list-group-item">Apresentação</li>
            <li class="list-group-item">Sessão</li>
            <li class="list-group-item">Transporte</li>
            <li class="list-group-item">Rede</li>
            <li class="list-group-item">Enlace</li>
            <li class="list-group-item">Fisica</li>
          </ul>
        </div>

      </div>

      <div class="d-flex flex-column">
        <div class="card" style="width: 8rem;">
          <ul class="list-group list-group-flush">
            <li class="list-group-item d-flex flex-row">
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp roxo"> <span id="hide">a</span> </div>
              <div class="boxp azul"> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp roxo"> <span id="hide">a</span> </div>
              <div class="boxp azul"> </div>
              <div class="boxp verde"> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp roxo"> <span id="hide">a</span> </div>
              <div class="boxp azul"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp lima"> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp roxo"> <span id="hide">a</span> </div>
              <div class="boxp azul"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp lima"> </div>
              <div class="boxp amarelo"> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp roxo"> <span id="hide">a</span> </div>
              <div class="boxp azul"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp lima"> </div>
              <div class="boxp amarelo"> </div>
              <div class="boxp laranja"> </div>
            </li>
            <li class="list-group-item d-flex flex-row">
              <div class="boxp roxo"> <span id="hide">a</span> </div>
              <div class="boxp azul"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp lima"> </div>
              <div class="boxp amarelo"> </div>
              <div class="boxp laranja"> </div>
              <div class="boxp vermelho"> </div>
            </li>
          </ul>
        </div>
      </div>

    </div>

  </div>
</template>

<!-- script -->
<script>
export default {
  data: function() {
    return {
    }
  },
  methods: {
    animarPassar: function() {
      let i = 0;
      this.chama(i)
    },
    chama: async function(i) {
      const timer = ms => new Promise(res => setTimeout(res, ms))
      var elemento = document.querySelectorAll("#primeiraCol>li");
      if(i<=elemento.length-1) {
        elemento[i].style.boxShadow = '0px 2px 22px #ff4242';
        i == 0 ? (i=0) : (elemento[i-1].style.boxShadow = '0px 2px 22px #ff4242');
        await timer(2000);
        console.log(i);
        i = i + 1;
        this.chama(i);
      }
    }
  }
}

</script>

<!-- CSS -->
<style>
  #hide { color: #595cf9 }
  li { font-weight: bold; }
  .boxp {
    width: 15rem;
    border-radius: 5px;
  }
  .roxo {
    background: #595cf9;
  }
  .azul {
    background: #59baf9;
  }
  .verde {
    background: #59f99d;
  }
  .lima {
    background: #a0f959;
  }
  .amarelo {
    background: #f3f959;
  }
  .laranja {
    background: #f99d59;
  }
  .vermelho {
    background: #f95959;
  }
  .focus {
    box-shadow: 0px 1px 35px #7bcafd;
  }

</style>
