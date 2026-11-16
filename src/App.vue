<script setup>
import RecipeForm from './components/RecipeForm.vue';
import Recipelist from './components/Recipelist.vue';
import RecipeCard from './components/RecipeCard.vue';
</script>

<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Receptkönyv</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="">Receptek<span class="sr-only"></span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="">Új recept</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="">Kedvencek</a>
      </li>
    </ul>
  </div>
</nav>

  </header>
  <main>
    <RecipeForm />
    <Recipelist />
    <RecipeCard />
  </main>
  <footer>

  </footer>
</template>

<style scoped> 

</style>