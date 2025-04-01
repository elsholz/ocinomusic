<template>
  <q-page class="column flex justify-center">
  <!--:style="`
                          background-image: url(/images/ocino_stage.jpeg);
                          background-position: center;
                          background-repeat: no-repeat;
                                              background-size: ${$q.screen.gt.xs ? $q.screen.gt.sm ? $q.screen.gt.md ? '100%' : '100%' : '100%' : '100%'};
                                              background-position: ${$q.screen.gt.xs ? 50 : 0}% 50%;`">-->
    <div class="row justify-center">
      <div class="col-lg-6 col-md-8 col-sm-10 col-xs-12 items-center">
        <q-parallax src="/images/ocino_stage_1000.jpg" :height="$q.screen.height">
          <div class="row full-width justify-center">
            <!--<div class="column col-4">
              <q-img src="/images/ocino_logo.png" sty>
              </q-img>
            </div>-->
            <div class="column col-10">
              <iframe
                style="border-radius:12px; opacity: 0.9;"
                src="https://open.spotify.com/embed/album/1xKMLqhapIc0vSoomSoAch?utm_source=generator"
                width="100%"
                :height="Math.min(512, $q.screen.height * .6)"
                frameBorder="0"
                allowfullscreen=""
                allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
                loading="lazy">
              </iframe>
            </div>
          </div>
        </q-parallax>
      </div>
    </div>

    <div class="row text-white text-h6 justify-center text-center">
      <div class="col-lg-6 col-md-8 col-sm-10 col-xs-12">
        <q-parallax src="/images/ocino_portrait_1000.jpg"
          :height="(($q.screen.height > 800) && ($q.screen.width > 480)) ? $q.screen.height : Math.max($q.screen.height, 900) * (480 / Math.min($q.screen.width, 480))">
          <div class="q-mx-sm">
            <span class="text-h3 ">about me.</span>
            <hr class="q-mb-lg" style="background-color: white; border: none; width: 300px; height: 2px;" />
            <p>
              OCINO is an up and coming singer & songwriter with unique sound and natural talent for crafting memorable
              songs.
            </p>
            <p>
              OCINO has been working tirelessly to hone his craft and create music that is both heartfelt and original.
            </p>
            <p>
              His songs often feature sing-along choruses and catchy melodies that get stuck in your head.
              His lyrics are also deeply personal and relatable, touching on themes of love, heartbreak, and the ups and
              downs
              of life.
            </p>
            <p>
              OCINO is not only a talented songwriter and musician but also a skilled producer.
              He produces all of his own music, giving him complete creative control over the final product.
            </p>
            <p>
              OCINO's hard work and dedication to his craft are paying off.
              He has several new songs in the works and continues writing, recording, and performing as much as possible.
            </p>
          </div>
        </q-parallax>
      </div>
    </div>

    <div class="row text-white text-center justify-center">
      <div class="col-lg-6 col-md-8 col-sm-10 col-xs-12">
        <q-parallax src="/images/ocino_stage_2_1000.jpg" :height="$q.screen.height">
          <div class="row">

            <span class="text-h3 col col-12">socials.</span>
            <hr class="q-mb-lg" style="background-color: white; border: none; width: 300px; height: 2px;" />
          </div>

          <div class="row">
            <div class="col-12 text-italic">
              <q-btn round flat padding="sm" size="4em" icon="fa-brands fa-instagram"
                href="https://instagram.com/itsnicosteger">
              </q-btn>
            </div>
          </div>
        </q-parallax>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'
import { useQuasar } from 'quasar'

export default defineComponent({
  name: 'IndexPage',
  setup: function () {
    const $q = useQuasar()
    console.log($q.screen.width, $q.screen.height)
    return {}
  },
  data () {
    return {
    }
  }
})
</script>
