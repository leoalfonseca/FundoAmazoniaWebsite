<template>
  <q-card flat class="bg-black"
    :style="$q.platform.is.mobile ? 'height: 6.7vh;' : $q.screen.lt.lg ? 'height: 110vh;' : 'height: 70vh;'">
    <q-card-section>
      <q-toolbar class="q-mt-xl">
        <q-space />
        <span class="text-white" style="font-size: 20px; font-weight: 400;">
          <strong>FALE CONOSCO</strong>
        </span>
        <q-space />

      </q-toolbar>

      <q-card-actions vertical align="center" class="text-white">

        <h4 style="font-weight: bold; text-align: center;"> GOSTOU DO NOSSO <br>
          <strong style="color: #00A39A">TRABALHO?</strong>

        </h4>
        <p style="text-align: center;">Entre em contato com a gente e faça parte do nosso time ajudando a <br>
          transformar o futuro através da sustentabilidade.</p>

      </q-card-actions>

      <q-toolbar>
        <q-space />
        <q-input dark dense class="text-grey q-mx-md q-mt-md" label="Nome:"
          :style="$q.platform.is.mobile ? 'width: 18rem' : 'width: 22rem'"></q-input>
        <q-input dark dense class="text-grey q-mx-md q-mt-md" label="Email:"
          :style="$q.platform.is.mobile ? 'width: 18rem' : 'width: 22rem'"></q-input>
        <q-input dark dense class="text-grey q-mx-md q-mt-md" label="Telefone"
          :style="$q.platform.is.mobile ? 'width: 18rem' : 'width: 22rem'"></q-input>
        <q-space />

      </q-toolbar>
      <q-toolbar>
        <q-space />
        <q-input dark dense type="textarea" class="text-grey q-mx-md q-mt-xl" label="Deixe sua mensagem:"
          :style="$q.platform.is.mobile ? 'width: 18rem' : 'width: 50rem'"></q-input>

        <q-space />

      </q-toolbar>
      <q-toolbar class="q-mt-lg">
        <q-space />
        <q-btn no-caps label="Enviar" color="primary"></q-btn>

      </q-toolbar>
    </q-card-section>
  </q-card>

  <q-card flat class="row bg-white"
    :style="$q.platform.is.mobile ? 'height: 6.7vh;' : $q.screen.lt.lg ? 'height: 85vh;' : 'height: 55vh;'">
    <q-card-section class="col-6">
      <q-card-section class="row">
        <q-card-actions vertical class="col-6">
          <q-btn flat label="FAO" class="q-mb-xl"> </q-btn>
          <q-btn flat no-caps label="O que é" class="q-mb-xl" href="https://www.fundoamazoniaoriental.org.br/o-que-e/">
          </q-btn>
          <q-btn flat no-caps label="Quem somos" class="q-mb-xl"
            href="https://www.fundoamazoniaoriental.org.br/quem-somos/"> </q-btn>
          <q-btn flat no-caps label="Quero fazer parte" class="q-mb-xl"
            href="https://www.fundoamazoniaoriental.org.br/quero-fazer-parte/como-funciona/"> </q-btn>
          <q-btn flat no-caps label="Transparência" class="q-mb-xl"
            href="https://www.fundoamazoniaoriental.org.br/transparencia/"> </q-btn>
          <q-btn flat no-caps label="Contexto" class="q-mb-xl" href="https://www.fundoamazoniaoriental.org.br/contexto/">
          </q-btn>
        </q-card-actions>
        <q-card-actions vertical class="col-6">
          <q-btn flat label="CONTATO" class="q-mb-xl"> </q-btn>
          <q-btn flat no-caps label="Fale Conosco" class="q-mb-xl"
            href="https://fundo_da_amazonia_oriental.wp.h6.homolog.inf.br/fale-conosco/">
          </q-btn>
          <q-btn flat no-caps label="R. Ver. Valdemar Ferreira de Aguiar, 13 - Cruzeiro, Tianguá - CE, 62322-090"
            class="q-mb-xl"
            href="https://www.google.com/maps/place/R.+31+de+Julho,+13+-+Cruzeiro,+Tianguá+-+CE,+62320-000/data=!4m2!3m1!1s0x7eb4900022d2b17:0x4d0d73edba45c9f3?sa=X&ved=2ahUKEwjDq9e2y8z9AhVhLbkGHQiACb0Q8gF6BAgVEAI">
          </q-btn>
          <q-btn flat no-caps label="21 2123-5300" class="q-mb-xl"></q-btn>

        </q-card-actions>

      </q-card-section>

    </q-card-section>

    <q-separator vertical style="height: 100%;" />

    <q-card-section class="col-4 q-mt-xl">

      <h3
        :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'font-size: 40px; width: 60.7vh' : 'height: 10.7vh; width: 65.7vh'"
        style="margin: 0%; color: #00A39A;">
        <strong> QUER RECEBER <br>
          NOTÍCIAS DO FAO?</strong>
      </h3>

      <q-input dense class=" q-mx-md q-mt-md" label="Nome:"
        :style="$q.platform.is.mobile ? 'width: 18rem' : 'width: 22rem'"></q-input>
      <q-input dense class=" q-mx-md q-mt-md" label="Email:"
        :style="$q.platform.is.mobile ? 'width: 18rem' : 'width: 22rem'"></q-input>
      <q-checkbox v-model="right" label="Aceito os Termos e Condições" />
      <q-space />
      <q-btn no-caps label="Assinar" color="primary" class="q-mt-md q-ml-md" style="width: 50%;"></q-btn>
    </q-card-section>

  </q-card>
  <q-separator></q-separator>
  <q-card flat class="row bg-white"
    :style="$q.platform.is.mobile ? 'height: 6.7vh;' : $q.screen.lt.lg ? 'height: 5vh;' : 'height: 5vh;'">
    <q-card-section class="col-6 flex flex-center">
      <p style="font-size: 10px;">Fundo da Amazônia Oriental Copyright (c)
        2022
        . Todos os direitos Reservados.</p>
    </q-card-section>
    <q-card-section class="col-6 flex flex-center">
      <q-btn flat no-caps href="https://www.okngroup.com.br" style="font-size: 10px;">Desenvolvido por OKN Technology
        Agency</q-btn>
    </q-card-section>
  </q-card>
</template>

<script>
import { ref } from 'vue'

export default {
  name: 'InfoFolder',

  // eslint-disable-next-line space-before-function-paren
  data() {
    return {
      right: ref(false)

    }
  }
}
</script>
