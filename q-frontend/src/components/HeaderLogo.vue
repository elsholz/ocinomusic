<template>
  <q-toolbar-title :class="
    $q.screen.gt.xs
      ? this.absoluteLeft === true
        ? 'absolute-left'
        : ''
      : 'absolute-center'
  ">
    <q-btn no-caps flat class="text-h6 q-px-xl" to="/" style="height:100px;" id="homebutton">
      <template v-if="$q.screen.gt.xs">
        <div style="line-height: 140%" class="text-center">
          <div class="row">
            <div class="text-bold q-pt-sm text-h5 q-pl-sm">OCINO MUSIC</div>
            <div class="text-weight-thin q-pl-lg text-monospace q-pt-sm"
              style="margin: 0; line-height: 110%; color: #c70">
            </div>
          </div>
        </div>
      </template>
      <template v-else>
        <div class="no-wrap row">
          <div class="col col-auto q-pt-sm q-pr-sm">
            <q-avatar square size="md" style="margin: 0; padding: 0">
              <img src="/icons/favicon-128x128.png" />
            </q-avatar>
          </div>
          <div class="col col-10">
            <div style="margin-bottom: 0">OCINO MUSIC</div>
          </div>
        </div>
      </template>
    </q-btn>
  </q-toolbar-title>
</template>

<style>
#homebutton:hover {
  background-size: cover;
  background-position: 50% 10%;
  background-repeat: no-repeat;

  background-image: url(/images/ocino_stage.jpeg);

  transition: 1s;
}
</style>

<script>
export default {
  name: 'HeaderLogo',
  setup () {
    return {}
  },
  props: {
    absoluteLeft: Boolean
  }
}
</script>
