<template>
  <q-page>
    <q-toolbar style="background-color: #00A39A;">
      <q-space />
      <q-btn flat no-caps class="text-white q-mx-lg" label="O que é"
        href="https://www.fundoamazoniaoriental.org.br/o-que-e/"></q-btn>
      <q-btn flat no-caps class="text-white q-mx-lg" label="Contexto"
        href="https://www.fundoamazoniaoriental.org.br/contexto/"></q-btn>
      <q-btn flat no-caps class="text-white q-mx-lg" label="Quem Somos"
        href="https://www.fundoamazoniaoriental.org.br/quem-somos/"></q-btn>

      <q-btn-dropdown class="q-mr-md text-white" flat no-caps label="Quero fazer parte">
        <q-list style="background-color: #00A39A;">
          <q-item clickable v-close-popup
            href="https://www.fundoamazoniaoriental.org.br/quero-fazer-parte/como-funciona/">
            <q-item-section avatar>
              <q-avatar icon="info" text-color="white" />
            </q-item-section>
            <q-item-section>
              <q-item-label class="text-white">Como funciona?</q-item-label>
            </q-item-section>
          </q-item>

          <q-item clickable v-close-popup
            href="https://www.fundoamazoniaoriental.org.br/quero-fazer-parte/portifolio-de-projetos/">
            <q-item-section avatar>
              <q-avatar icon="folder" text-color="white" />
            </q-item-section>
            <q-item-section>
              <q-item-label class="text-white">Portfólio de Projetos</q-item-label>
            </q-item-section>
          </q-item>

        </q-list>
      </q-btn-dropdown>

      <q-btn-dropdown class="text-white" flat no-caps label="Transparência">
        <q-list style="background-color: #00A39A;">
          <q-item clickable v-close-popup href="https://www.fundoamazoniaoriental.org.br/transparencia/atas/">
            <q-item-section avatar>
              <q-avatar icon="folder" text-color="white" />
            </q-item-section>
            <q-item-section>
              <q-item-label class="text-white">Atas</q-item-label>
            </q-item-section>
          </q-item>

          <q-item clickable v-close-popup href="https://www.fundoamazoniaoriental.org.br/transparencia/relatorios/">
            <q-item-section avatar>
              <q-avatar icon="summarize" text-color="white" />
            </q-item-section>
            <q-item-section>
              <q-item-label class="text-white">Relatórios</q-item-label>
            </q-item-section>
          </q-item>

          <q-item clickable v-close-popup href="https://www.fundoamazoniaoriental.org.br/transparencia/legislacao/">
            <q-item-section avatar>
              <q-avatar icon="gavel" text-color="white" />
            </q-item-section>
            <q-item-section>
              <q-item-label class="text-white">Legislação</q-item-label>
            </q-item-section>
          </q-item>

        </q-list>
      </q-btn-dropdown>
      <q-btn flat no-caps class="text-white q-mx-lg" label="Fale Conosco"
        href="https://www.fundoamazoniaoriental.org.br/fale-conosco/"></q-btn>
      <q-space />

    </q-toolbar>

    <InfoFolder></InfoFolder>
    <InfoProjectsTabs></InfoProjectsTabs>
    <InfoFolder2></InfoFolder2>
    <InfoContact></InfoContact>

  </q-page>
</template>

<script>

import InfoFolder from 'src/components/InfoFolder.vue'
import InfoProjectsTabs from 'src/components/InfoProjectsTabs.vue'
import InfoFolder2 from 'src/components/InfoFolder2.vue'
import InfoContact from 'src/components/InfoContact.vue'

export default {
  name: 'IndexPage',

  components: {
    InfoFolder,
    InfoProjectsTabs,
    InfoFolder2,
    InfoContact
  }
}
</script>
