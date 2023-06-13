<template>
  <q-layout view="hHh lpR fff">
    <q-header
      elevated
    >
      <q-toolbar class=""
    style="height:100px"
      >
        <HeaderLogo :absolute-left='true'> </HeaderLogo>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <PageFooter></PageFooter>
  </q-layout>
</template>

<script>
import { defineComponent } from 'vue'
import HeaderLogo from 'src/components/HeaderLogo.vue'
import PageFooter from 'src/components/PageFooter.vue'

export default defineComponent({
  name: 'MainLayout',
  setup () {
    const staging = process.env.Env === 'dev'
    return {
      staging
    }
  },
  components: { HeaderLogo, PageFooter }
})
</script>
