# 🦎 Lizard Hunt

**Lizard Hunt** è un puzzle logico in cui devi trovare tutte le lucertoline nascoste all'interno di una griglia colorata.

Non serve fortuna: la posizione delle lucertole può essere dedotta usando esclusivamente le regole del gioco. 🧠🦎

## 🎮 Come si gioca

La griglia è divisa in diverse **aree colorate**.

Ogni area può contenere **al massimo una lucertola**.

Le lucertole devono inoltre rispettare queste regole:

- 🦎 Non possono esserci due lucertole sulla stessa riga.
- 🦎 Non possono esserci due lucertole sulla stessa colonna.
- 🦎 Due lucertole non possono essere adiacenti, nemmeno diagonalmente.
- 🦎 Ogni area colorata può contenere al massimo una lucertola.
- 🦎 Il numero totale di lucertole corrisponde al numero di righe della griglia.

### 🦎 Trovare una lucertola

La modalità **🦎 Trova lucertola** serve per tentare di trovare una lucertola.

Quando clicchi una casella:

- se contiene davvero una lucertola, viene mostrata 🦎;
- se è vuota, il tentativo è sbagliato.

Non puoi quindi piazzare lucertole liberamente: **la lucertola appare solo quando hai trovato la posizione corretta**.

### ❌ Segnare una casella

La modalità **❌ Segna X** permette di segnare le caselle che pensi siano sicuramente vuote.

Le X sono solamente degli appunti e non contano come tentativi.

## 🧠 Generazione matematica

Lizard Hunt non utilizza una soluzione casuale.

La soluzione viene generata tramite un algoritmo di **ricerca dei vincoli (backtracking)** che rispetta matematicamente le regole delle lucertole.

Il gioco verifica inoltre le possibili soluzioni del puzzle e cerca di utilizzare configurazioni con **una sola soluzione possibile**.

Per questo motivo il puzzle può essere risolto usando la logica, senza dover indovinare.

## 📏 Dimensioni

Puoi scegliere diverse dimensioni della griglia:

- 4 × 4
- 5 × 5
- 6 × 6
- 7 × 7
- 8 × 8
- 9 × 9
- 10 × 10

Sono inoltre disponibili diversi livelli di difficoltà.

## 🏆 Obiettivo

L'obiettivo è trovare **tutte le lucertole** con il minor numero possibile di errori.

Ragiona sulle:

- righe;
- colonne;
- aree colorate;
- posizioni già escluse;
- lucertole già trovate.

Più informazioni raccogli, più facile diventa dedurre le posizioni rimanenti.

## 📥 Scarica

### Versione 1.0

Puoi scaricare il gioco in un singolo file HTML:

- [Scarica Lizard Hunt 1.0](version-1.0/DeMENIGECO.Games.LHunt.html)

Non è necessario installare nulla.

È sufficiente aprire il file `.html` con un browser.

## 💻 Tecnologie

Lizard Hunt è realizzato interamente con:

- HTML
- CSS
- JavaScript

Non richiede server, database o connessione a Internet.

## 📜 Licenza

Questo progetto fa parte dei giochi web di **DeMENIGECO Games**.
