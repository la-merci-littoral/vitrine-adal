<script setup lang="ts">

import '@fontsource/krona-one';
import '@fontsource/orienta';

</script>

<template>
  <div id="info-wrapper">
    <h2>Raccourcis</h2>
    <div id="links">
      <a href="https://adhesion.amis-du-littoral.fr"><button>Adhésion à l'association</button></a>
      <a href="https://inscription.amis-du-littoral.fr"><button>Inscription aux évènements</button></a>
    </div>
  </div>
</template>

<style scoped>
  #info-wrapper {
    padding: 20px 40px;
    border-radius: 25px;
    color: white;
    background-color: #2c7ba8;
    border: 2px solid #1d338f;

    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
  }

  h2 {
    font-family: 'Krona One', sans-serif;
    text-align: center;
    margin-bottom: 20px;
  }

  div#links {
    margin-top: 10px;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
    gap: 10px;
  }

  #adal-whole {
    font-size: 80%;
  }

  #links button {
    font-family: 'Orienta', sans-serif;
    margin-top: 15px;
    font-size: 120%;
    padding: 10px;
    background-color: #0e3d85;
    color: white;
    border: none;
    border-radius: 5px;
    transition: background-color ease .15s;
  }

  #links button:hover {
    background-color: #2c567e;
    transition: background-color ease .15s;
    cursor: pointer;
  }

</style>
