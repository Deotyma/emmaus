<template>
  <div>
  <b-navbar toggleable="lg" type="dark" class="navigation sticky-top">
    <img src="../assets/logo-tremma-emmaus.0f7f9fa5.svg" class="logo">

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" class="row justify-content-md-center" is-nav>
      <b-navbar-nav>
        <b-nav-item href="https://www.tremma.co/qui-sommes-nous">Qui sommes nous?</b-nav-item>
        <b-nav-item href="https://www.tremma.co/c/comment-ca-marche">Comment ça marche?</b-nav-item>
        <b-nav-item href="https://www.tremma.co/c/comment-ca-marche">Acheter un objet</b-nav-item>
        <b-button class="mr-3" variant="light" href="https://www.tremma.co/projets-actifs">Donner un objet</b-button>
        <b-button class="mr-3" variant="outline-light" href="https://www.tremma.co/mon-compte">Connexion</b-button>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.navigation{
  background-color: #e72560;
  font-size: medium;
}
a.btn-light{
  color: #e72560;
}
.logo{
  height: 2em;
}


</style>