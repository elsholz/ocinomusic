<template>
  <q-page class="column flex q-pb-xl items-center "
    style="background-image: url(/images/ocino_stage.jpeg); background-position: center; background-size: 80%; background-repeat: no-repeat;;">
    <div class="row q-my-md q-mt-xl">
      <div class="col text-h6 text-center col-12">
        Willkommen bei
      </div>
      <div class="col text-h4 text-center col-12">
        <pre><code style="color:#3f5; background-color:#203; border-radius: 5px;"> ocino music </code></pre>
      </div>
    </div>
    <div class="row q-my-md">
      <div class="col text-body1 text-center column col-12">
        <q-btn outline no-wrap no-caps to="/me" color="yellow">
          Über mich
        </q-btn>
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
