<template>
  <q-page padding dark class="justify-center flex row items-center">
    <div class="column col col-lg-6 col-md-8 col-sm-12 q-px-sm text-body1 text-center">
      <div class="row q-pt-md text-white text-center">
        <div class="col-12">
          <h3>Projektvorstellung</h3>
        </div>
      </div>
      <div class="row q-pt-md text-white text-center">
        <div class="col-12">
          <q-avatar square size="150px" class="q-ma-sm">
            <img src="/icons/mpl_logo.svg" />
          </q-avatar>
        </div>
      </div>
      <div class="row text-white text-center q-pb-md">
        <div class="col-12 text-h5">OCINO MUSIC</div>
      </div>
      <div class="row text-white text-center q-pb-xl">
        <div class="col-12 text-italic">
          Hier findet ihr uns auch:<br />
          <q-btn round flat padding="sm" size="xl" icon="fa-brands fa-github"
            href="https://github.com/elsholz/ocinomusic"></q-btn>
          <q-btn round flat padding="sm" size="xl" icon="fa-brands fa-instagram"
            href="https://instagram.com/ocinomusic"></q-btn>
        </div>
      </div>

      <div class="row text-white text-center">
        <div class="col-12 text-h6">Absatztitel</div>
        <hr style="background-color: white; width: 300px" />
      </div>
      <div class="row text-white text-justify q-pb-lg">
        <div class="col-12">
          <p>
            Absatz-Inhalt
          </p>
          <ol>
            <li>
              Liste
            </li>
          </ol>
        </div>
      </div>

      <div class="row text-white text-center">
        <div class="col-12 text-h6">Über mich</div>
        <hr style="background-color: white; width: 300px" />
      </div>
      <div class="row text-white text-center">
        <div class="col-12">Das bin ich, Nico:</div>
      </div>
      <div class="q-col-gutter-md text-white row items-start">
        <div class="col-12" style="height:500px">
          <q-img src="/images/ocino_stage.jpeg">
          </q-img>
        </div>
      </div>
      <div class="row text-white text-center q-mb-xl">
        <div class="col-12">
          <p>
            Absatz zentriert
          </p>
          <p>
            Absatz zentriert 2
          </p>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  setup () {
    return {}
  }
}
</script>
