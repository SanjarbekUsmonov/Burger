<template>
  <q-layout view="hhh lpR fff">
    <q-header class="bg-white text-white row justify-center content-center" style="height: 100px">
      <div class="header row justify-between items-start content-center">
        <div class="logo row content-center" style="width: 20%; height: 100px">
          <q-img src="https://foodsify.xyz/uploads/logo.png" style="width: 215px; height: 45px" />
        </div>
        <div class="home" style="width: 45%; height: 100px">
          <ul class="ul fit row justify-between items-start content-center">
            <li><a href=""></a> Home</li>
            <li><a href=""></a> About</li>
            <li><a href=""></a> Pricing</li>
            <li><a href=""></a> Democ</li>
            <li><a href=""></a> Blogs</li>
            <li><a href=""></a> Contact</li>
          </ul>
        </div>
        <div class="select" style="width: 30%; height: 100px">
          <div class="fit row justify-end items-start content-center">
            <select name="" id="" style="padding: 13px; margin-right: 8px; border-radius: 4px">
              <option value="eng">English</option>
              <option value="rus">Russki</option>
              <option value="uzb">Uzbek</option>
            </select>
            <q-btn color="black" class="btn" padding="13px 35px" label="Become A Partner" />
          </div>
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
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg" />
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
.header {
  width: 85%;
  height: 100px;
}

.ul li {
  list-style: none;
  font-size: 16px;
  margin-bottom: 20px;
  color: grey;
}

.ul li:hover {
  cursor: pointer;
  color: green;
  transition: 0.5s;
}

.btn {
  border-radius: 4px;
  font-size: 12px;
}
</style>
