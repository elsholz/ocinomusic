<template>
  <q-page class="column flex q-pb-xl items-center " :style="`
        background-image: url(/images/ocino_stage.jpe);
        background-position: center;
        background-repeat: no-repeat;
            background-size: ${$q.screen.gt.xs ? $q.screen.gt.sm ? $q.screen.gt.md ? '100%' : '100%' : '100%' : '100%'};
            background-position: ${$q.screen.gt.xs ? 50 : 0}% 50%;`">
    <!--<div class="row q-my-md q-mt-xl">
      <div class="col text-h6 text-center col-12">
        Willkommen bei
      </div>
      <div class="col text-h4 text-center col-12">
        <pre><code style="color:#3f5; background-color:#203; border-radius: 5px;"> ocino music </code></pre>
      </div>
    </div>-->

    <div class="row q-my-md">
      <div class="col text-body1 text-center column col-12">
        <q-img src="/images/ocino_stage.jpeg" :style="`width: ${$q.screen.gt.xs ? $q.screen.gt.sm ? 60 : 80 : 100}vw;`">
        </q-img>
      </div>
    </div>

    <div class="row q-my-xl">
      <div class="col text-center column col-12 text-white">
        <q-btn outline no-wrap class="text-h6" no-caps to="/me" color="secondary" icon-right="fa-solid fa-music">
          about me
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
