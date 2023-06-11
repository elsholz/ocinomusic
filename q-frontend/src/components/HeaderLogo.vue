<template>
  <q-toolbar-title :class="
    $q.screen.gt.xs
      ? 'absolute-left'
      : 'absolute-center'
  ">
    <q-btn no-caps flat class="text-h6" to="/" style="height:100px; width: 222px;" id="homebutton">
      <div class="column col-6 q-mb-lg">
        <q-img src="/images/ocino_logo.png" style="width: 100px" />
      </div>
      <div class="column col-6 q-mb-lg">
        <div class="text-bold q-pt-sm text-h5 q-pl-sm q-mb-sm" style="line-height: 100px; vertical-align: middle;">MUSIC</div>
      </div>
    </q-btn>
  </q-toolbar-title>
</template>

<style>
#homebuttonbackground:hover {
  background-size: cover;
  background-position: 50% 10%;
  background-repeat: no-repeat;
  background-image: url(/images/ocino_stage.jpeg);
}

#homebuttonbackground {
  position: relative;
  top: 0; left: 0;
  width: 100%;
  height: 100%;
  background-image: none;
  transition: all 2s;
  opacity: 1;
}
</style>

<script>
export default {
  name: 'HeaderLogo',
  setup () {
    return {}
  }
}
</script>
