<template>
  <q-tabs v-model="tab" no-caps dense class="text-grey" active-color="primary" indicator-color="primary" align="left" caps
    inline-label>
  </q-tabs>
  <q-tab-panels v-model="tab" animated class="bg-primary">

    <q-tab-panel name="tabProjeto1">
      <q-card class="row" style="height: 74vh; background-color: #00A39A;">
        <q-card-section class="col-6 flex-center flex">

          <q-card-section class="no-padding q-mt-md" style=" width: 50vh;">

            <q-toolbar class="no-padding q-mb-lg">
              <q-toolbar-title class="brownfont " style="letter-spacing: 0.2em; font-size: 17px; font-weight: 400;">
                NOSSOS PROJETOS
              </q-toolbar-title>
            </q-toolbar>

            <h3
              :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 60.7vh'"
              style="margin: 0%;">
              <strong>PROJETO PLANTANDO</strong><strong style="color: #FFFFFF"> OPORTUNIDADES</strong>
            </h3>

            <q-scroll-area class="q-mt-xl"
              :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height:  12.7vh; width: 70.7vh' : 'height: 22.7vh; width: 60.7vh'">
              <h7>
                O FAO é uma estratégia de financiamento ambiental pautada em colaborações privadas, em prol do
                fortalecimento
                das políticas públicas e das iniciativas sociais focadas em meio ambiente e desenvolvimento no Pará. Os
                programas e projetos apoiados visam a construção de novas iniciativas para a agenda climática do Pará,
                objetivando impactos para as comunidades, escalabilidade e compromisso com as metas globais.
                <br><br>
                Conheça os nossos programas e projetos e faça parte dessa estratégia.
              </h7>
            </q-scroll-area>
            <q-toolbar>
              <q-btn rounded outline :ripple="{ color: 'black' }" class="q-ml-lg text-white"
                href="https://www.fundoamazoniaoriental.org.br/projetos/projeto-fortalecimento-do-fundo-da-amazonia-oriental/">
                <span>Saiba mais</span>
              </q-btn>
              <q-btn rounded outline :ripple="{ color: 'black' }" class="q-ml-xs text-white" icon="north_east"
                href="https://www.fundoamazoniaoriental.org.br/projetos/projeto-fortalecimento-do-fundo-da-amazonia-oriental/">
              </q-btn>
            </q-toolbar>
          </q-card-section>

        </q-card-section>

        <q-card-section class="col-6 flex-inline flex">
          <q-img src="../assets/cachoeira.png"
            :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 60.7vh;' : 'height: 70.7vh;'">
            <div class="absolute-right text-subtitle2">
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto1'" label="1" />

              </div>
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto2'" label="2" />

              </div>
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto3'" label="3" />

              </div>

            </div>
          </q-img>
        </q-card-section>

      </q-card>
    </q-tab-panel>

    <q-tab-panel name="tabProjeto2">
      <q-card class="row" style="height: 74vh; background-color: #00A39A;">
        <q-card-section class="col-6 flex-center flex">

          <q-card-section class="no-padding q-mt-md" style=" width: 50vh;">

            <q-toolbar class="no-padding q-mb-lg">
              <q-toolbar-title class="brownfont " style="letter-spacing: 0.2em; font-size: 17px; font-weight: 400;">
                NOSSOS PROJETOS
              </q-toolbar-title>
            </q-toolbar>

            <h3
              :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 65.7vh'"
              style="margin: 0%;">
              <strong>PROJETO</strong><strong style="color: #FFFFFF"> CAR 2.0 </strong><strong>"FASE 1" -- <br>
                TRANSFORMAÇÃO DIGITAL</strong>
            </h3>

            <q-scroll-area class="q-mt-xl"
              :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height:  12.7vh; width: 70.7vh' : 'height: 22.7vh; width: 60.7vh'">
              <h7>
                Apoiar a implementação do sistema CAR 2.0, por meio da transformação digital da SEMAS, garantindo a
                qualidade e a segurança dos dados, bem como o desenvolvimento de um sistema para readequação ambiental e
                comercial para pequenos produtores que integram a cadeia da pecuária no Estado do Pará.
              </h7>
            </q-scroll-area>
            <q-toolbar>
              <q-btn rounded outline :ripple="{ color: 'black' }" class="q-ml-lg text-white"
                href="https://www.fundoamazoniaoriental.org.br/projetos/projeto-car-2-0-fase-1-transformacao-digital/">
                <span>Saiba mais</span>
              </q-btn>
              <q-btn rounded outline :ripple="{ color: 'black' }" class="q-ml-xs text-white" icon="north_east"
                href="https://www.fundoamazoniaoriental.org.br/projetos/projeto-car-2-0-fase-1-transformacao-digital/">
              </q-btn>
            </q-toolbar>
          </q-card-section>

        </q-card-section>

        <q-card-section class="col-6 flex-inline flex">
          <q-img src="../assets/projetocar2.0.png"
            :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 60.7vh;' : 'height: 70.7vh;'">
            <div class="absolute-right text-subtitle2">
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto1'" label="1" />

              </div>
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto2'" label="2" />

              </div>
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto3'" label="3" />

              </div>

            </div>
          </q-img>
        </q-card-section>

      </q-card>
    </q-tab-panel>

    <q-tab-panel name="tabProjeto3">
      <q-card class="row" style="height: 74vh; background-color: #00A39A;">
        <q-card-section class="col-6 flex-center flex">

          <q-card-section class="no-padding q-mt-md" style=" width: 50vh;">

            <q-toolbar class="no-padding q-mb-lg">
              <q-toolbar-title class="brownfont " style="letter-spacing: 0.2em; font-size: 17px; font-weight: 400;">
                NOSSOS PROJETOS
              </q-toolbar-title>
            </q-toolbar>

            <h3
              :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 65.7vh'"
              style="margin: 0%;">
              <strong>PROJETO</strong><strong style="color: #FFFFFF"> TRANSFORMAÇÃO </strong><strong>DIGITAL,
                COMUNICAÇÃO E <br>
                TRANSPARÊNCIA</strong>
            </h3>

            <q-scroll-area class="q-mt-xl"
              :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height:  12.7vh; width: 70.7vh' : 'height: 22.7vh; width: 60.7vh'">
              <h7>
                Apoiar as ações de transformação digital da SEMAS e permitir o fortalecimento de ações voltadas à
                comunicação e transparência do FAO.
              </h7>
            </q-scroll-area>
            <q-toolbar>
              <q-btn rounded outline :ripple="{ color: 'black' }" class="q-ml-lg text-white"
                href="https://www.fundoamazoniaoriental.org.br/projetos/projeto-transformacao-digital-comunicacao-e-transparencia/">
                <span>Saiba mais</span>
              </q-btn>
              <q-btn rounded outline :ripple="{ color: 'black' }" class="q-ml-xs text-white" icon="north_east"
                href="https://www.fundoamazoniaoriental.org.br/projetos/projeto-transformacao-digital-comunicacao-e-transparencia/">
              </q-btn>
            </q-toolbar>
          </q-card-section>

        </q-card-section>

        <q-card-section class="col-6 flex-inline flex">
          <q-img src="../assets/projeto3.png"
            :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 60.7vh;' : 'height: 70.7vh;'">
            <div class="absolute-right text-subtitle2">
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto1'" label="1" />

              </div>
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto2'" label="2" />

              </div>
              <div>
                <q-btn class="q-my-lg" outline color="primary" @click="this.tab = 'tabProjeto3'" label="3" />

              </div>

            </div>
          </q-img>
        </q-card-section>

      </q-card>
    </q-tab-panel>

  </q-tab-panels>

  <q-toolbar style="background-color: #00A39A;">
    <q-btn style="height: 100%; width: 100%;"
      href="https://www.fundoamazoniaoriental.org.br/quero-fazer-parte/portifolio-de-projetos/">
      <span>VER TODOS OS PROJETOS</span>
      <q-icon class="q-ml-md" name="arrow_right_alt" />
    </q-btn>
  </q-toolbar>
</template>

<script>
import { ref } from 'vue'

export default {
  name: 'InfoProjectsTabs',

  // eslint-disable-next-line space-before-function-paren
  data() {
    return {
      video: false,
      tab: ref('tabProjeto3')
    }
  }
}
</script>
