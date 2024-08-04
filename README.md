# Progetto Presto.it

Progetto Presto.it è una piattaforma di annunci che consente agli utenti di vendere prodotti online in modo semplice e veloce, o di salvarne alcuni fra i preferiti per poter contattare in seguito il venditore.

## Descrizione

Progetto Presto.it è stato sviluppato per offrire un'esperienza di shopping online intuitiva e sicura. Gli utenti possono registrarsi, creare profili, pubblicare annunci per vendere i propri prodotti e visualizzare articoli caricati da altri utenti. La piattaforma include funzionalità di ricerca avanzata, gestione degli ordini e sistema di valutazione e feedback per gli utenti. Il sito supporta inoltre un numero espansibile di linguaggi, con la traduzione completa di ogni singola interfaccia e menù. Vi sono inoltre i controlli tramite AI per il riconoscimento e la censura dei volti e per il filtraggio delle foto, le quali prima di essere pubblicate devono risultare rispettose degli standard comunitari.

## Tecnologie Utilizzate

- **Frontend**: 
  - HTML5
  - CSS3
  - JavaScript
  - Vue.js

- **Backend**: 
  - PHP
  - Laravel

- **Database**: 
  - MySQL

- **Altro**:
  - Composer (per la gestione delle dipendenze PHP)
  - NPM/Yarn (per la gestione delle dipendenze JavaScript)
  - Bootstrap (per lo styling del frontend)

## Installazione

Per eseguire questo progetto in locale, segui questi passaggi:

1. Clona il repository:
   ```bash
   git clone https://github.com/VincenzoBuonanova/Progetto_Presto.it.git
   cd Progetto_Presto.it
   
2. Installa le dipendenze PHP con Composer:
   ```bash
   composer install

3. Installa le dipendenze JavaScript:
   ```bash
   npm install

4. Configura il file .env con le informazioni del tuo database.

5. Esegui le migrazioni del database:
   ```bash
   php artisan migrate

6. Avvia il lavoratore delle code di Laravel:
   ```bash
   php artisan queue:work

7. Gestisci le risorse del frontend:
   ```bash
   npm run dev

8. Avvia il server di sviluppo:
   ```bash
   php artisan serve
