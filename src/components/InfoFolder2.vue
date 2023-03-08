<template>
  <q-card flat class="row" style="height: 70vh;">
    <q-card-section class="col-6 flex-center flex">
      <q-card-section class="no-padding q-mt-md" style="width: 50vh;">

        <q-toolbar class="no-padding q-mb-lg" style="width: 65vh;">
          <q-space />
          <span class="brownfont " style="letter-spacing: 0.2em; font-size: 17px; font-weight: 400;">
            COMO FUNCIONA
          </span>
        </q-toolbar>

        <h3 dir="rtl"
          :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 65.7vh'"
          style="margin: 0%;">
          <strong style="color: #00A39A"> UMA VERDADEIRA REVOLUÇÃO AMBIENTAL</strong>
        </h3>

        <q-scroll-area class="q-mt-xl q-ml-xl"
          :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height:  12.7vh; width: 70.7vh' : 'height: 22.7vh; width: 60.7vh'">
          <h7>
            Juntar forças em prol da neutralidade climática é a oportunidade que o Pará quer para fazer a diferença. Com
            recursos que podem vir de múltiplas origens, podendo ser tanto de obrigações legais quanto de doações, o FAO é
            um fundo que o Governo incentiva, a Sociedade conduz e o mundo apoia. Todos ganham.
          </h7>
        </q-scroll-area>

        <q-toolbar style="width: 65vh;">
          <q-space />
          <q-btn rounded outline :ripple="{ color: 'primary' }" class="q-ml-lg"
            href="https://www.fundoamazoniaoriental.org.br/quero-fazer-parte/como-funciona/">
            <span>ENTENDA</span>
          </q-btn>
          <q-btn rounded outline :ripple="{ color: 'primary' }" class="q-ml-xs" icon="north_east"
            href="https://www.fundoamazoniaoriental.org.br/quero-fazer-parte/como-funciona/">
          </q-btn>
        </q-toolbar>
      </q-card-section>
    </q-card-section>
    <q-card-section class="col-6 flex-center flex">
      <q-img src="../assets/projetocarbarraverde.png" style="position: relative; float: right;"
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 80vh width:30vh' : 'height: 50vh; width:70vh;'" />
    </q-card-section>
    <q-toolbar>

      <q-space />
      <q-img src="../assets/quadradoverde.png" style="position: relative; float: right;"
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 10vh; width:12vh' : 'height: 10vh; width:12vh;'">
      </q-img>
      <q-space />

    </q-toolbar>
  </q-card>

  <q-card flat class="row" style="height: 70vh;">

    <q-card-section class="col-6 bg-primary flex-center flex">
      <q-card-section style="border: #FFFFFF solid 0.5px;"
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 68.7vh; width: 85.7vh' : 'height: 60.7vh; width: 80.7vh'">
        <q-img src="../assets/comunicaçãoresponsabilidadefolder.png"></q-img>
      </q-card-section>
    </q-card-section>

    <q-card-section class="col-6 flex-center flex">
      <q-toolbar class="no-padding q-mb-lg" style="width: 65vh;">
        <span class="brownfont " style="letter-spacing: 0.2em; font-size: 17px; font-weight: 400;">
          NOSSOS VALORES
        </span>
      </q-toolbar>

      <h3
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 65.7vh'"
        style="margin: 0%;">
        <strong> NOSSO JEITO DE <br>
          OBSERVAR O MUNDO</strong>
      </h3>

      <q-scroll-area class="q-mt-xl q-mr-xl"
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height:  12.7vh; width: 70.7vh' : 'height: 22.7vh; width: 60.7vh'">
        <h7>
          Uma Amazônia conservada e com qualidade de vida para os cerca de 30 milhões de habitantes, que tenha como bases
          o desenvolvimento sustentável, a redução das desigualdades; o desenvolvimento socioeconômico de baixo carbono; a
          participação social; a equidade de gênero; e o planejamento de longo prazo associado a uma visão sistêmica.
        </h7>
      </q-scroll-area>

    </q-card-section>

  </q-card>

  <q-card flat class="row" style="height: 50vh;">
    <q-card-section class="col-5 q-mt-xl">
      <q-card-actions align="center">
        <q-toolbar class="no-padding q-mb-lg" style="width: 65vh;">
          <span class="brownfont " style="letter-spacing: 0.2em; font-size: 17px; font-weight: 400;">
            NA MÍDIA
          </span>
        </q-toolbar>

        <h3
          :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 65.7vh'"
          style="margin: 0%;">
          <strong>SAIBA O QUE <br>
            ESTÃO FALANDO<br> DE NÓS</strong>
        </h3>

      </q-card-actions>

    </q-card-section>

    <q-card-section class="q-mt-xl col-2">
      <q-img src="../assets/belemnoticia.png" />
      <q-btn label="Leia Mais" color="primary" style="width: 100%;"
        href="https://www.paraterraboa.com/economia/fundo-amazonia-oriental-deve-entrar-em-operacao-em-outubro/"></q-btn>
    </q-card-section>

    <q-card-section class="q-mt-xl col-2">
      <q-img src="../assets/paranoticia.png" />
      <q-btn label="Leia Mais" color="primary" style="width: 100%;"
        href="https://www.belemnegocios.com/post/fundo-da-amazonia-oriental-capta-6-milhoes-em-5-meses"></q-btn>

    </q-card-section>

    <q-card-section class="q-mt-xl col-2">
      <q-img src="../assets/cbnnoticia.png" />
      <q-btn label="Leia Mais" color="primary" style="width: 100%;"
        href="https://cbnamazonia.com/cidades/belem/fundo-amazonia-oriental-recebe-1-milhao-para-projetos-do-plano-amazonico-agora"></q-btn>

    </q-card-section>

  </q-card>
</template>

<script>
export default {
  name: 'InfoFolder',

  // eslint-disable-next-line space-before-function-paren
  data() {
    return {

    }
  }
}
</script>
