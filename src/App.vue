<template>
  <div id="app">
    <div>
  <b-nav class="navigation">
    <b-nav-item href="https://www.tremma.co/qui-sommes-nous">Qui sommes nous</b-nav-item>
    <b-nav-item >Link</b-nav-item>
    <b-nav-item>Another Link</b-nav-item>
    <b-nav-item disabled>Disabled</b-nav-item>
  </b-nav>
</div>

    <router-view/>
  </div>
</template>

<style>
.navigation{
  background-color: blueviolet;
}

</style>
