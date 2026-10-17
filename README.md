# Laboratorio IA e processi dell'ente — Reggio Emilia

Web app statica in **un solo file HTML**, senza backend, database, framework, CDN o dipendenze esterne.

## Pubblicazione su GitHub Pages

1. Crea un repository pubblico (es. `laboratorio-ia-processi`).
2. Carica `index.html` nella radice del repository.
3. In **Settings → Pages**, scegli **Deploy from a branch**, branch **main**, cartella **/(root)**, e salva.
4. Dopo la pubblicazione, il sito sarà indicativamente su `https://TUO-UTENTE.github.io/laboratorio-ia-processi/` (verifica l'indirizzo effettivo in Settings → Pages).

Puoi aprire `index.html` direttamente nel browser per provarlo, anche offline.

## Caratteristiche

- Sei tappe progressive, progettate per un laboratorio di 60 minuti.
- Timer facoltativo e indicatore di completamento.
- Caso fittizio caricabile come dimostrazione.
- Salvataggio automatico tramite `localStorage` **solo nel browser corrente**.
- Importazione/esportazione JSON, riepilogo copiabile e stampa/salvataggio PDF.
- Tutti i contenuti sono editabili, anche nel sorgente HTML.
- Nessun dato inviato a server dall'applicazione.

## Attenzione ai dati

Non inserire dati personali, riservati o relativi a pratiche reali. I dati restano nella memoria locale del browser fino alla cancellazione, ma possono essere accessibili a chi utilizza lo stesso profilo/dispositivo. Su computer condivisi usare «Cancella dati da questo browser». Un export JSON o PDF contiene quanto inserito dagli utenti e va conservato in modo appropriato.

## Adattamento

Testi, colori e logica sono tutti contenuti nel file `index.html` (sezioni `<style>` e `<script>`). Non serve compilare nulla.
