<template>
  <q-card class="row" style="height: 80vh;">
    <q-card-section class="col-6 flex-center flex">
      <q-card-section style="border: solid 0.5px;"
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 68.7vh; width: 85.7vh' : 'height: 60.7vh; width: 80.7vh'">

        <q-toolbar>
          <q-toolbar-title class="q-ml-lg brownfont " style="letter-spacing: 0.2em; font-size: 17px; font-weight: 400;">
            FUNDO DA AMAZÔNIA
          </q-toolbar-title>
        </q-toolbar>

        <q-card-section class="" style="width: 50vh;">
          <h3
            :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 60.7vh'"
            style="margin: 0%;">
            TRANSFORMANDO <strong style="color: #00A39A">O MUNDO</strong> ATRAVÉS
          </h3>
          <h3 style="margin: 0%;"
            :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 80.7vh' : 'height: 10.7vh; width: 60.7vh'">

            <strong style="color: #00A39A"> DA
              SUSTENTABILIDADE</strong>
          </h3>
          <q-scroll-area class="q-mt-xs"
            :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height:  12.7vh; width: 70.7vh' : 'height: 12.7vh; width: 70.7vh'">
            <span>
              Comprometido com a redução do desmatamento ilegal e a emissão de Gases de Efeito Estufa (GEE) no território
              paraense, bem como com o cumprimento de metas previstas nas políticas públicas de meio ambiente e
              desenvolvimento, o Estado do Pará criou o Fundo da Amazônia Oriental (FAO). Um mecanismo operacional e
              financeiro privado para apoio às políticas públicas e iniciativas sociais, que visa impulsionar o
              desenvolvimento sustentável no Pará.
            </span>
          </q-scroll-area>
        </q-card-section>
        <q-toolbar class="q-mt-lg">
          <q-btn rounded outline :ripple="{ color: 'primary' }" class="q-ml-lg">
            <span>Saiba mais</span>
          </q-btn>
          <q-btn rounded outline :ripple="{ color: 'primary' }" class="q-ml-xs" icon="north_east">
          </q-btn>
        </q-toolbar>
      </q-card-section>

    </q-card-section>
    <q-card-section class="col-6 no-padding">
      <q-img src="../assets/firstgif.gif"
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 80vh width:30vh' : 'height: 80vh width:30vh;'" />

    </q-card-section>

  </q-card>

  <q-card class="row" style="height: 80vh;">
    <q-card-section class="col-6 flex flex-center">
      <q-img src="../assets/governador.png" style="position: relative; float: right;"
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 80vh width:30vh' : 'height: 50vh; width:70vh;'" />

    </q-card-section>

    <q-card-section class="col-6">

      <q-card-section style="position: relative; top: 15%;">

        <q-toolbar>
          <q-toolbar-title class="brownfont " style="letter-spacing: 0.2em; font-size: 17px; font-weight: 400;">
            QUEM SOMOS
          </q-toolbar-title>
        </q-toolbar>

        <q-card-section class="no-padding q-mt-md" style="width: 50vh;">
          <h3
            :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 60.7vh'"
            style="margin: 0%; color: #00A39A">
            <strong>CUIDANDO DO SEU FUTURO NO PRESENTE</strong>
          </h3>

          <q-scroll-area class="q-mt-xl"
            :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height:  12.7vh; width: 70.7vh' : 'height: 22.7vh; width: 60.7vh'">
            <h7>
              Um fundo privado que congrega diferentes atores do Poder Público e sociedade civil, para a estruturação de
              um modelo de desenvolvimento baseado na conservação e na valorização de ativos ambientais no Pará.
              <br><br>
              Com uma governança desenhada em diferentes níveis de atuação, o FAO conta com a participação de
              representantes: dos Doadores e Financiadores, do Poder Público, da Sociedade Civil e do Setor Privado. Uma
              multiplicidade de visões, que olham para o futuro, por meio de ações agora.
            </h7>
          </q-scroll-area>
        </q-card-section>
        <q-toolbar>
          <q-btn rounded outline :ripple="{ color: 'primary' }" class="q-ml-lg">
            <span>Saiba mais</span>
          </q-btn>
          <q-btn rounded outline :ripple="{ color: 'primary' }" class="q-ml-xs" icon="north_east">
          </q-btn>
        </q-toolbar>
      </q-card-section>
    </q-card-section>

  </q-card>
  <q-card style="height: 110vh;">
    <q-toolbar style="height: 30vh;">
      <q-space />
      <q-img class="q-mr-md" src="../assets/circuloverde.png"
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 5.7vh; width: 5.7vh' : 'height: 5.7vh; width: 5.7vh'">
      </q-img>
      <h4 style="font-weight: bold;">
        JUNTE-SE A NÓS E <br>
        <strong style="color: #00A39A">FAÇA PARTE</strong><br>
        DESSA MUDANÇA
      </h4>
      <q-space />

    </q-toolbar>
    <q-video v-model="video" style="height: 80vh;" src="https://www.youtube.com/embed/5g8IyHvVBL8?autoplay=1">
    </q-video>

  </q-card>
</template>

<script>
export default {
  name: 'InfoFolder'

}
</script>
