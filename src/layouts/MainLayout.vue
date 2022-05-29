<template>
  <q-layout view="hhh lpR fff">

    <q-header class="bg-white text-white row justify-center content-center" style="height: 100px">
      <div class="header  row  justify-between items-start content-center">
          <div class="logo bg-red" style="width: 20%;height: 100px; ">

          </div>
          <div class="home bg-green" style="width: 45%;height: 100px;">

          </div>
          <div class="select bg-blue" style="width: 30%;height: 100px;">

          </div>
      </div>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-grey-8 text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
          <div>Title</div>
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>

  </q-layout>
</template>
<script>

</script>
<style>
.header{
  width: 85%;
  height: 100px;
  background-color: yellow;
}


</style>
