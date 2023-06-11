<template>
  <q-page padding dark class="justify-center flex row items-center" id="mepage"
  :style="`background-size: ${$q.screen.gt.xs ? $q.screen.gt.sm ? $q.screen.gt.md ? '50%' : '75%' : '100%' : '150%'};
  background-position: ${$q.screen.gt.xs ? 50: 0}% 50%;`">
    <div class="column col col-lg-6 col-md-6 col-sm-12 q-px-sm text-body1 text-center">
      <div class="row q-pt-md text-white text-center">
        <div class="col-12">
          <h3>about me</h3>
        </div>
      </div>

      <div class="row text-white text-center q-mb-xl">
        <div class="col-12">
          <p>
            OCINO is an up and coming singer, songwriter, and producer who is quickly making a name for himself in the
            music industry. With a unique sound and a natural talent for crafting memorable songs, OCINO is poised for a
            bright future in the music industry.
          </p>
          <p>
            Born in Germany, OCINO grew up surrounded by music. At the age of 15, he started playing guitar and writing
            songs, and by 21, he had moved to Berlin to pursue his musical dreams.
          </p>
          <p>
            Since then, OCINO has been working tirelessly to hone his craft and create music that is both heartfelt and
            original.
          </p>
          <p>
            One of OCINO's biggest strengths as a musician is his ability to write catchy, memorable hooks. His songs
            often feature sing-along choruses and catchy melodies that get stuck in your head for days. His lyrics are
            also deeply personal and relatable, touching on themes of love, heartbreak, and the ups and downs of life.
          </p>
          <p>
            OCINO is not only a talented songwriter and musician but also a skilled producer. He produces all of his own
            music, which gives him complete creative control over the final product. His attention to detail and
            commitment to quality is evident in the polished sound of his recordings.
          </p>
          <!--<p>
            OCINO's hard work and dedication to his craft are paying off. He has several new songs in the works and plans
            to continue writing, recording, and performing as much as possible. With his talent, drive, and passion for
            music, there's no doubt that he has a bright future ahead.
          </p>-->
        </div>
      </div>

      <div class="row text-white text-center">
        <div class="col-12 text-h6">Socials</div>
        <hr style="background-color: white; width: 300px" />
      </div>
      <div class="row text-white text-center q-pb-xl">
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
