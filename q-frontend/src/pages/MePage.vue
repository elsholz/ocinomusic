<template>
  <q-page padding dark class="justify-center flex row items-center" id="mepage" :style="`background-size: ${$q.screen.gt.xs ? $q.screen.gt.sm ? $q.screen.gt.md ? '50%' : '75%' : '100%' : '150%'};
              background-position: ${$q.screen.gt.xs ? 50 : 0}% 50%;`">
    <div class="column col col-lg-6 col-md-6 col-sm-12 q-px-sm text-justify">
      <div class="row text-white text-center">
        <div class="col-12">
          <h3>about me.</h3>
        </div>
      </div>

      <div class="row text-white text-center text-h6 q-mb-lg">
        <div class="col-12">
          <p>
            OCINO is an up and coming singer & songwriter with unique sound and natural talent for crafting memorable songs.
          </p>
          <p>
            OCINO has been working tirelessly to hone his craft and create music that is both heartfelt and original.
          </p>
          <p>
            His songs often feature sing-along choruses and catchy melodies that get stuck in your head.
            His lyrics are also deeply personal and relatable, touching on themes of love, heartbreak, and the ups and downs of life.
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
      </div>

      <div class="row text-white text-center">
        <div class="col-12 text-h6">Socials</div>
        <hr style="background-color: white; width: 300px" />
      </div>
      <div class="row text-white text-center q-pb-lg">
        <div class="col-12 text-italic">
          <q-btn round flat padding="sm" size="xl" icon="fa-brands fa-github"
            href="https://github.com/elsholz/ocinomusic"></q-btn>
          <q-btn round flat padding="sm" size="xl" icon="fa-brands fa-instagram"
            href="https://instagram.com/ocinomusic"></q-btn>
        </div>
      </div>
    </div>
  </q-page>
</template>

<style>
#mepage {
  background-image: url(/images/ocino_portrait_smol.jpeg);
  box-shadow: inset 0 0 0 1000px rgba(0, 0, 0, .5);
  background-position: center;
  background-repeat: no-repeat;
}
</style>

<script>
export default {
  setup () {
    return {}
  }
}
</script>
