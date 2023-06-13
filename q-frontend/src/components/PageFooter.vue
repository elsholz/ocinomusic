<template>
  <q-footer class="bg-grey-8 text-white">
    <q-toolbar>
      <q-toolbar-title>
        <q-btn round flat padding="xs" size="lg" icon="fa-brands fa-github" href="https://github.com/elsholz/ocinomusic"></q-btn>
        <q-btn round flat padding="xs" size="lg" icon="fa-brands fa-instagram" href="https://instagram.com/itsnicosteger"></q-btn>
        <!--<q-btn round flat padding="xs" size="lg" icon="fa-brands fa-facebook"></q-btn>-->
        <!--<q-btn round flat padding="xs" size="lg" icon="fa-brands fa-btc"></q-btn>-->
        <!--<q-btn round flat padding="xs" size="lg" icon="fa-brands fa-reddit"></q-btn>-->
      </q-toolbar-title>

      <q-btn no-caps flat class="text-grey-4" to="/impressum">impressum</q-btn>
    </q-toolbar>
  </q-footer>
</template>

<script>
export default {
  name: 'PageFooter',
  setup () {
    return {}
  }
}
</script>
