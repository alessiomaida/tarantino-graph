# Tarantino · grafo delle influenze

Grafo interattivo (D3.js) dei crediti dei film di Quentin Tarantino e delle opere che li hanno ispirati: film, musica, letteratura, serie TV, registi e autori.

- Due versioni da confrontare, con selettore in alto nella barra laterale:
  - **v2** (`v2.html`): tutto il grafo con filtri
  - **v3** (`index.html`): navigazione progressiva. Si parte da Tarantino e dai 10 film, si aprono i nodi con un click (`+n` = collegamenti nascosti), modalità Focus con 1-2 salti e percorso di navigazione
- Tre viste di contenuto: Tutto / Crediti / Influenze
- Ogni collegamento di influenza ha una fonte web e un livello di affidabilità (dichiarato, documentato, critica, interpretativo)
- Dati in `data.json` (compilati a mano a partire da fonti web, non da OMDb)

Demo: https://alessiomaida.github.io/tarantino-graph/
