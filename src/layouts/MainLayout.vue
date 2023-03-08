<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated style="background-color: #FFFFFF;">
      <q-toolbar :style="$q.platform.is.mobile ? 'height: 13vh' : $q.screen.lt.lg ? 'height:13.7vh' : 'height: 8.7vh'">
        <q-space />

        <q-img src="../assets/fundoamazoniaheader.png"
          :style="$q.platform.is.mobile ? 'height: 6.7vh; width: 30.7vh' : $q.screen.lt.lg ? 'height: 10.7vh; width: 30.7vh' : 'height: 6.7vh; width: 20.7vh'">
        </q-img>

        <q-space />
        <q-space />
        <q-space />

        <q-input outlined dense label="Faça uma busca" :style="$q.platform.is.mobile ? 'width: 18rem' : 'width: 22rem'">
          <template #append>
            <q-icon name="search" />
          </template>
        </q-input>

        <q-space />
        <q-space />
        <q-space />

        <q-btn class="q-mx-sm mobile-hide" :ripple="{ color: 'black' }"
          href="https://www.fundoamazoniaoriental.org.br/fale-conosco/">
          <img src="../assets/facebookbtn.png" />
        </q-btn>
        <q-btn class="q-mx-sm mobile-hide" :ripple="{ color: 'black' }"
          href="https://www.fundoamazoniaoriental.org.br/fale-conosco/">
          <img src="../assets/instagrambtn.png" />
        </q-btn>

        <q-btn class="q-mx-sm q-px-sm mobile-hide" :ripple="{ color: 'black' }" dense label="QUERO PARTICIPAR"
          href="https://www.fundoamazoniaoriental.org.br/fale-conosco/" style="background-color: #00A39A;" />

      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import {
  defineComponent
} from 'vue'

export default defineComponent({
  name: 'MainLayout',

  components: {},

  // eslint-disable-next-line space-before-function-paren
  setup() {
    return {}
  }
})
</script>
