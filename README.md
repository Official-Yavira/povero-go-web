# POVERО GO — Web Prototype

Versione web prototipale in evoluzione. Repository separato dal progetto Unity mobile.

## Funzioni presenti
- Home e navigazione responsive
- Forest Run 3D nel browser tramite Three.js: tre corsie, cambio corsia, salto, scivolata, ostacoli, monete, punteggio e game over
- Scansione da fotocamera o galleria con risultato simulato
- Bestiario con 12 specie, rarità e ruoli
- Negozio cosmetico con crediti virtuali
- Missioni e ricompense
- Profilo e progressi salvati in localStorage
- Classifica locale dimostrativa

## Limiti da non confondere con funzioni attive
Il riconoscimento AI non è collegato: la scansione assegna una specie dimostrativa. Account, database, sincronizzazione, classifica globale, pagamenti e protezione anti-abuso richiedono un backend e non sono attivi. I dati sono salvati solo nel browser corrente. La scena 3D usa geometrie procedurali temporanee: modelli premium, rig, animazioni e texture finali sono ancora da produrre.

## Avvio
La pagina carica Three.js come modulo ES da CDN, quindi apri tramite GitHub Pages o un server statico locale (ad esempio Live Server), non con doppio clic su file://.

## Struttura
- index.html: schermate e struttura
- style.css: interfaccia responsive
- game.js: logica e scena Three.js

## Pubblicazione
Repository Settings → Pages → Deploy from a branch → main → /(root).
