<template>
  <q-page class="doc-container flex flex-center bg-primary q-pb-xl">
    <div class="col text-white" style="max-width: 1000px">
      <div class="row justify-center q-my-md">
        <div class="text-h6 text-center col-12">
          Willkommen bei
        </div>
        <div class="row justify-center">
          <div class="text-h4 text-center col-12">
            <pre><code style="color:#3f5; background-color:#203; border-radius: 5px;"> ocino music </code></pre>
          </div>
        </div>
        <div class="q-mt-lg row justify-center">
          <div class="text-body1 text-center column col-sm-8 col-xs-12 q-px-xs">
            Metroplanner ist ein Webtool zur Erstellung und zum Anzeigen von
            intuitiven und diagramm-ähnlichen Liniennetzplänen für den ÖPNV.
            Aufgrund der einfachen Bedienung eignet sich Metroplanner
            insbesondere zur Erstellung von Netzplänen in kleineren Städten und
            Gemeinden, die heute häufig noch keine derartigen Pläne besitzen.<br>
          </div>
        </div>
        <div class="q-mt-lg row justify-center">
          <div class="text-body1 text-center column col-12">
            <q-btn outline no-wrap no-caps to="/me" color="green">
              Über mich
            </q-btn>
          </div>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage',
  data () {
    return {
    }
  }
})
</script>
