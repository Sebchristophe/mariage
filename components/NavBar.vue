<template>
<div>
  <b-navbar id="thenavbar" toggleable="lg">
    <b-navbar-brand id="titre">Mariage Seb & Steph</b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav >
      <b-navbar-nav justified:true right>
        <b-nav-item href="#">Accueil</b-nav-item>
        <b-nav-item href="#">Lieu</b-nav-item>
        <b-nav-item-dropdown text="Photos" right>
          <b-dropdown-item href="#">Avant</b-dropdown-item>
          <b-dropdown-item href="#">Vins d'honneur</b-dropdown-item>
          <b-dropdown-item href="#">Soirée</b-dropdown-item>
          <b-dropdown-item href="#">Week-end</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="Invités" right>
          <b-dropdown-item href="#">Mon espace</b-dropdown-item>
          <b-dropdown-item href="#">Déconnexion</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>

  </b-navbar>
</div>
</template>

<script>
export default {
  name: "NavBar"
}
</script>

<style scoped>
#titre, #nav-collapse{
  color: #d1d59f;
}
#thenavbar {
  background-color: #b694b4;
  font-family: 'Alex Brush';
  font-size: 28px;
  font-weight: bold;
  text-shadow:2px 2px 2px #5c5b81;
  color: #d1d59f;

}

.navbar > li > a{
  font-size: 2rem;
}

</style>
