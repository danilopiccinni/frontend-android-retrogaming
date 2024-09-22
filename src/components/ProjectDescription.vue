<script>
export default {
  name: 'ProjectDescription',
};
</script>

<template>
  <div class="description-container">

    <h1>Complete ROM Manager for Android</h1>
    <p>
      This project aims to build a sophisticated frontend for organizing and managing a large collection of game ROMs, categorized by console type. 
      Each category will be linked to a specific emulator (e.g., Nintendo, Super Nintendo), leveraging the best existing Android emulators to provide a smooth and integrated gaming experience.
      The ultimate goal is to create a powerful and intuitive hub for retro gaming enthusiasts.
    </p>
    <h2>Main Features:</h2>
    <ul>
      <li><strong>Console-based Categorization</strong>: The app will classify games by console, automatically selecting the correct emulator for each category.</li>
      <li><strong>Dynamic Game Information</strong>: Each game will have a detailed card with title, cover image, description, and genre. These details will be gathered via a custom web scraper, ensuring complete and accurate data.</li>
      <li><strong>Search and Filters</strong>: Users will be able to search for games by name, category, or genre, providing quick and intuitive access to the desired content.</li>
      <li><strong>Emulator Integration</strong>: The project will support multiple emulators, automatically launching the correct one based on the selected ROM.</li>
      <li><strong>Future Features</strong>: This frontend will continuously evolve, adding new features to ensure it remains a cutting-edge solution for retro gaming.</li>
    </ul>
    <p>
      This ambitious project aims to consolidate various tools and technologies, creating a unified platform for managing game ROMs and emulators. As the project progresses, new features and integrations will be added to further enhance the user experience.
    </p>

    <h1>Gestore Completo di ROM di Giochi per Android</h1>
    <p>
      Questo progetto si propone di costruire un frontend sofisticato per organizzare e gestire un'ampia collezione di ROM di giochi, suddivisa per tipo di console. 
      Ogni categoria sarà collegata a un emulatore specifico (ad esempio, Nintendo, Super Nintendo), sfruttando i migliori emulatori esistenti per Android per offrire un'esperienza di gioco fluida e integrata.
      L'obiettivo finale è creare un hub potente e intuitivo per gli appassionati di retro gaming.
    </p>
    <h2>Caratteristiche principali:</h2>
    <ul>
      <li><strong>Suddivisione per Console</strong>: L'app classificherà i giochi in base alla console di appartenenza, selezionando automaticamente l'emulatore corretto per ogni categoria.</li>
      <li><strong>Informazioni Dinamiche sui Giochi</strong>: Ogni gioco avrà una scheda dettagliata con titolo, immagine di copertina, descrizione e genere. Questi dati verranno raccolti tramite uno scraper web personalizzato, garantendo informazioni complete e accurate.</li>
      <li><strong>Ricerca e Filtri</strong>: Gli utenti potranno cercare i giochi per nome, categoria o genere, offrendo un accesso rapido e intuitivo ai contenuti desiderati.</li>
      <li><strong>Integrazione con Emulatori</strong>: Il progetto supporterà più emulatori, lanciando automaticamente quello corretto in base alla ROM selezionata.</li>
      <li><strong>Funzionalità Future</strong>: Questo frontend evolverà continuamente, includendo nuove funzionalità per assicurarsi che rimanga una soluzione all'avanguardia per il retro gaming.</li>
    </ul>
    <p>
      Questo progetto ambizioso mira a consolidare vari strumenti e tecnologie, creando una piattaforma unificata per la gestione di ROM di giochi ed emulatori. Man mano che il progetto progredirà, verranno aggiunte nuove funzioni e integrazioni per migliorare ulteriormente l'esperienza utente.
    </p>
  </div>
</template>

<style scoped>
.description-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  text-align: center;
  background-color: #d5d5d5;
  border-radius: 10px;
  box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
}

h1 {
  color: #2c3e50;
  font-size: 2.5em;
  font-family: 'Poppins', sans-serif;
  margin-bottom: 20px;
  letter-spacing: 1px;
}

p {
  color: #34495e;
  font-size: 1.2em;
  font-family: 'Roboto', sans-serif;
  line-height: 1.6;
}

.description-container:hover {
  background-color: #eef2f3;
}

h1:hover {
  color: #42b983;
}

p:hover {
  color: #2980b9;
}
</style>
