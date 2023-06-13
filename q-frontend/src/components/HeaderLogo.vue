<template>
  <q-toolbar-title class="absolute-center">
    <q-btn no-caps flat class="text-h6" to="/" style="height:100px; width: 222px;" id="homebutton">
      <div class="column col-12 items-center">
        <q-img src="/images/ocino_logo.png" style="width: 150px" />
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
