<script>
//Importiamo i componenti da usare
import AppTitle from './components/AppTitle.vue'


//Definiamo l'oggetto che conterrà la lista dei componenti importati, che vogliamo usare
export default {
  components: {
    AppTitle,
 
  }
}
</script>

<!-- Qui inseriamo l'HTML della nostra App -->
<template>
  <div></div>
  <header>
    
    <!-- Usiamo i componenti importati sopra -->
    <!-- il contenuto è nei relativi file (cartella "components") -->
    <AppTitle />
  </header>


</template>

<!-- Qui abbiamo eventuale stile del componente "App", che è il contenitore generale -->
<style></style>