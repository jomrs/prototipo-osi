<template>
  <div class="prototipo justify-content-center">

    <div class="d-flex justify-content-right" style="height: 2.5rem; margin-left: 12px;">
      <button type="button" class="btn btn-primary" v-on:click='animarPassar'><b-icon-play></b-icon-play> Start </button>
      <button class="btn btn-secondary" style="margin-left:10px;" v-on:click="aniState==false ? aniState=true: aniState=false"><b-icon-pause></b-icon-pause> Pause </button>
    </div>

    <!-- primeira coluna -->
    <div class="d-flex flex-row container justify-content-center">

      <div class="flex-column" style="margin-right:12px;">
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title" id="camadaName">Inicie a simulação.</h5>
            <p class="card-text" id="camadaInfo" style="text-align: left;">Informações da camamada são exibidas aqui.</p>
            <b-icon-box-seam></b-icon-box-seam>
          </div>
        </div>
        <br>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Protocolos da camada</h5>
            <p class="card-text" id="protocolos">Protocolos.</p>
            <b-icon-bricks></b-icon-bricks>
          </div>
        </div>
        
      </div>

      <div class="d-flex flex-column">
        <div class="card" style="width: 8rem;">
          <ul class="list-group list-group-flush"  id="primeiraCol">
            <li class="list-group-item d-flex flex-row" style="justify-content:flex-end;">
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row" style="justify-content:flex-end;">
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row" style="justify-content:flex-end;">
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row" style="justify-content:flex-end;">
              <div class="boxp lima"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row" style="justify-content:flex-end;">
              <div class="boxp amarelo"> </div>
              <div class="boxp lima"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row" style="justify-content:flex-end;">
              <div class="boxp laranja"> </div>
              <div class="boxp amarelo"> </div>
              <div class="boxp lima"> </div>
              <div class="boxp verde"> </div>
              <div class="boxp azul"> </div>
              <div class="boxp roxo"> <span id="hide">a</span> </div>
            </li>
            <li class="list-group-item d-flex flex-row" style="justify-content:flex-end;">
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
        <div class="card" style="width: 12rem; margin-left:10px;">
          <ul class="list-group list-group-flush">
            <li class="list-group-item" style="background:#595cf9; color:#2d2d2d;">Aplicação</li>
            <li class="list-group-item" style="background:#59baf9; color:#2d2d2d;">Apresentação</li>
            <li class="list-group-item" style="background:#59f99d; color:#2d2d2d;">Sessão</li>
            <li class="list-group-item" style="background:#a0f959; color:#2d2d2d;">Transporte</li>
            <li class="list-group-item" style="background:#f3f959; color:#2d2d2d;">Rede</li>
            <li class="list-group-item" style="background:#f99d59; color:#2d2d2d;">Enlace</li>
            <li class="list-group-item" style="background:#f95959; color:#2d2d2d;">Fisica</li>
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
        
      <div style="margin-top:10px;">
      <div class="card d-flex flex-row justify-content-between" style="width: 250px; position: absolute; margin-left:-90px; background: #383838; color: #f7f7f7;">
        <b-icon-box style="margin-right:22px; margin-left: 4px; margin-top: 2px; margin-bottom: 2px;"></b-icon-box>
        <b-icon-arrow-right style="margin-top: 2px;"></b-icon-arrow-right>
        <b-icon-box style="margin-left: 22px; margin-top: 2px; margin-right: 4px;"></b-icon-box>
      </div>
    </div>
      </div>

      <div class="d-flex flex-column">
        <div class="card" style="width: 12rem; margin-right:10px;">
          <ul class="list-group list-group-flush">
            <li class="list-group-item" style="background:#595cf9; color:#2d2d2d;">Aplicação</li>
            <li class="list-group-item" style="background:#59baf9; color:#2d2d2d;">Apresentação</li>
            <li class="list-group-item" style="background:#59f99d; color:#2d2d2d;">Sessão</li>
            <li class="list-group-item" style="background:#a0f959; color:#2d2d2d;">Transporte</li>
            <li class="list-group-item" style="background:#f3f959; color:#2d2d2d;">Rede</li>
            <li class="list-group-item" style="background:#f99d59; color:#2d2d2d;">Enlace</li>
            <li class="list-group-item" style="background:#f95959; color:#2d2d2d;">Fisica</li>
          </ul>
        </div>

      </div>

      <div class="d-flex flex-column">
        <div class="card" style="width: 8rem;">
          <ul class="list-group list-group-flush"  id="segundaCol">
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
import osi from '../../public/osi.json';
export default {
  data: function() {
    return {
      osiInfo: osi,
      aniState: false
    }
  },
  methods: {
    animarPassar: function() {
      this.ida(0);
    },
    ida: async function(i) {
      const timer = ms => new Promise(res => setTimeout(res, ms))
      var elemento = document.querySelectorAll("#primeiraCol>li");
      if(i<=6) {
        elemento[i].style.boxShadow = '0px 2px 22px #59baf9';
        i == 0 ? (i=0) : (elemento[i-1].style.boxShadow = '');
        this.osiDados(i);
        await timer(3000);
        while(this.aniState) { await timer(1000); }
        i = i + 1;
        this.ida(i);
      } else { this.volta(i-1) }
    },
    volta: async function(i) {
      const timer = ms => new Promise(res => setTimeout(res, ms))
      var elemento = document.querySelectorAll("#segundaCol>li");
      if(i>=0) {
        elemento[i].style.boxShadow = '0px 2px 22px #59baf9';
        i == 6 ? (document.querySelectorAll("#primeiraCol>li")[6].style.boxShadow = '') : (elemento[i+1].style.boxShadow = '');
        this.osiDados(i);
        await timer(3000);
        while(this.aniState) { await timer(1000); }
        this.volta(i-1);
      }
    },
    osiDados: function(i) {
      document.querySelectorAll("#camadaName")[0].innerText = "Camada: " + this.osiInfo[i].camada;
      document.querySelectorAll("#camadaInfo")[0].innerText = this.osiInfo[i].info;
      document.querySelectorAll("#protocolos")[0].innerText = this.osiInfo[i].protocolos;
    }
  }
}

</script>

<!-- CSS -->
<style>
  #hide { color: #595cf9 }
  li { font-weight: bold; }
  .boxp {
    width: 12px;
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
