# 🧭 Laboratorio IA e processi dell’Ente

**Laboratorio IA e processi dell’Ente** è un’attività collaborativa per riprogettare un processo amministrativo introducendo un solo passaggio assistito dall’IA: dall’idea al primo esperimento, mantenendo controllo umano, fonti affidabili e responsabilità chiare.

L’obiettivo non è automatizzare un procedimento, ma progettare un punto di supporto che l’ente potrebbe valutare, autorizzare e sperimentare.

## 🎯 A chi è rivolto

Il laboratorio è pensato per:

- dirigenti e responsabili di servizio;
- funzionari ed esecutori della Pubblica Amministrazione;
- referenti ICT, RTD, privacy, sicurezza e trasformazione digitale;
- gruppi di lavoro che vogliono esplorare l’uso dell’IA nei processi;
- formatori che vogliono condurre un laboratorio pratico di 60 minuti.

## 🧠 L’idea

Molte iniziative sull’IA partono dalla tecnologia: “quale modello usiamo?”.

Questo laboratorio parte dal processo: **quale attività vogliamo migliorare, dove l’IA può aiutare davvero e chi deve controllare il risultato?**

La regola è semplice:

> L’IA produce soltanto una bozza o un supporto verificabile. La decisione, la validazione e la responsabilità restano alle persone competenti.

## 🕹️ Come funziona

Il laboratorio è progettato per **60 minuti**, da svolgere in piccoli gruppi, attraverso sei tappe progressive.

| Tappa | Durata | Attività |
|---:|---:|---|
| 1. **Il processo** | 5 minuti | Scegliere un processo o attività da migliorare e definire il risultato atteso. |
| 2. **Prima / dopo** | 10 minuti | Mappare il flusso attuale, individuare un solo passaggio assistito dall’IA e descrivere il flusso proposto. |
| 3. **Modello condiviso** | 10 minuti | Trasformare un prompt personale in un modello condiviso, con nome, versione, istruzioni e campi variabili. |
| 4. **Fonti e strumenti** | 10 minuti | Individuare le fonti autorizzate, chi le aggiorna e quale architettura merita una valutazione. |
| 5. **Governance e sperimentazione** | 15 minuti | Definire owner, verifiche, limiti, primo esperimento, metrica e decisione necessaria. |
| 6. **Restituzione** | 10 minuti | Presentare la proposta del gruppo in massimo due minuti. |

## 🧩 Il percorso del gruppo

### 1. Il processo

Il gruppo sceglie un’attività ripetitiva, anche non necessariamente automatizzabile, e descrive:

- il processo da migliorare;
- chi è coinvolto;
- il risultato osservabile che si vuole ottenere.

Non basta dire “risparmiare tempo”: serve un vantaggio concreto e verificabile.

### 2. Prima e dopo

Il gruppo mappa il flusso attuale in 3–5 passaggi, poi inserisce **un solo passaggio assistito dall’IA**.

L’IA può preparare una sintesi, una tabella o una bozza. Non prende decisioni, non firma e non invia nulla da sola.

### 3. Dal prompt personale al modello condiviso

Un modello condiviso ha:

- uno scopo;
- una versione;
- un responsabile;
- fonti ammesse;
- limiti d’uso;
- una posizione dove conservare la copia attiva.

Non è una copia sparsa di una conversazione con un chatbot.

### 4. Fonti e architetture

Il gruppo individua le fonti autorizzate e chi le mantiene aggiornate.

L’app propone alcune opzioni da valutare:

- prompt e documenti selezionati;
- RAG su base documentale governata;
- connettori o MCP con permessi;
- modello locale o ambiente controllato;
- combinazione da progettare con ICT/RTD.

La scelta non deve essere la più sofisticata, ma quella **proporzionata all’esigenza e al rischio**.

### 5. Governance e sperimentazione

Il gruppo definisce:

- l’owner del modello o del processo;
- chi verifica output e fonti;
- le verifiche indispensabili;
- quando non usare il modello;
- il primo esperimento realizzabile;
- la metrica per misurare l’utilità;
- la decisione necessaria prima di partire.

Il primo esperimento deve essere piccolo, reversibile, basato su casi fittizi o pubblici e accompagnato da autorizzazioni adeguate.

### 6. Restituzione

Ogni gruppo presenta la propria proposta in massimo **2 minuti**, rispondendo a tre domande:

- Il cambiamento è utile e misurabile?
- Chi governa istruzioni, dati e risultato?
- Quale decisione della direzione serve prima di iniziare?

## 🧪 Caso fittizio

L’app include un esempio caricabile, utile come dimostrazione:

> Un servizio riceve molte richieste di informazioni sui documenti necessari per un procedimento. L’IA potrebbe preparare una bozza di risposta usando FAQ e regolamenti pubblici aggiornati; il personale controlla il risultato prima dell’invio.

Il caso è interamente fittizio e può essere sostituito con una descrizione generica di un processo reale, senza inserire dati sensibili.

## 💻 Funzionalità

- Sei tappe progressive per un laboratorio di 60 minuti.
- Timer facoltativo e indicatore di completamento.
- Caso fittizio caricabile come dimostrazione.
- Salvataggio automatico tramite `localStorage`, solo nel browser corrente.
- Importazione ed esportazione della scheda in JSON.
- Riepilogo copiabile.
- Stampa o salvataggio in PDF.
- Contenuti editabili anche nel sorgente HTML.
- Nessun dato inviato a server dall’applicazione.

## 💻 Come usare l’app

L’app è una **web app statica autonoma**, contenuta in un unico file `index.html`.

- Non richiede account o registrazione.
- Non utilizza modelli IA connessi o servizi esterni.
- Non invia dati a server.
- Funziona nel browser e può essere usata offline dopo l’apertura del file.

### Avvio locale

1. Scarica o clona il repository.
2. Apri `index.html` con un browser moderno.
3. Avvia il laboratorio e compila la scheda del gruppo.

### Clonare il repository

```bash
git clone [https://github.com/gigicogo/lab-processi-ia.git](https://github.com/gigicogo/lab-processi-ia.git)
cd lab-processi-ia
```

## 🔐 Attenzione ai dati

Non inserire dati personali, riservati o relativi a pratiche reali.

- I dati restano nella memoria locale del browser fino alla cancellazione.
- Possono essere accessibili a chi utilizza lo stesso profilo o dispositivo.
- Su computer condivisi, usare **“Cancella dati da questo browser”** al termine.
- Un export JSON o PDF contiene quanto inserito dagli utenti e va conservato in modo appropriato.

## 🛠️ Personalizzazione

Tutto il contenuto è contenuto nel file `index.html`.

Puoi adattare:

- titoli e testi delle sei tappe;
- esempi e caso fittizio;
- campi della scheda;
- opzioni di architettura;
- colori e layout tramite le variabili CSS in `:root`.

## 🧪 Possibili evoluzioni

- Aggiunta di nuovi casi per diversi settori della PA.
- Versione multi-gruppo con confronto delle proposte.
- Esportazione in Markdown o PDF strutturato.
- Versione inglese del laboratorio.
- Integrazione con checklist di governance e valutazione dei rischi.
- Modelli di scheda per diversi tipi di processo.

## 🤝 Contribuire

Sono benvenuti suggerimenti su nuovi casi, miglioramenti didattici, correzioni e materiali di supporto.

1. Apri una Issue per proporre un’idea o segnalare un problema.
2. Oppure apri una Pull Request con una modifica o un nuovo caso.
3. Mantieni la struttura a sei tappe e l’attenzione a controllo umano, fonti e governance.

---

## 📄 Licenza

Da definire: si suggerisce una licenza aperta (es. MIT o CC BY 4.0) per favorire il riuso da parte di altri formatori o altri enti. Sostituisci questo paragrafo con il testo della licenza scelta e il file `LICENSE` del repo.

## 👤 Autore e contesto

**Gianluigi Cogo**  
Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa nella Pubblica Amministrazione.

L’app nasce come esercitazione nel percorso operativo **“L’IA nella Pubblica Amministrazione — Percorso operativo per l’uso consapevole, sicuro e governato dell’IA generativa”** (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti). Per info sul corso contattami usando i social qui sotto.

- 📮 **Newsletter:** [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 **Blog:** [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ **YouTube:** [youtube.com/@gigicogo](https://youtube.com/@gigicogo)
- 💼 **LinkedIn:** [linkedin.com/in/gigicogo](https://www.linkedin.com/in/gigicogo)
