# Progetto NewS: Relazione Interdisciplinare

Il progetto NewS è un ecosistema digitale complesso che coinvolge diversi ambiti disciplinari, combinando elementi di informatica, design e business. Questi settori interagiscono sinergicamente per creare un'esperienza utente completa e coinvolgente. Di seguito vengono esplorati i collegamenti interdisciplinari all'interno di questo progetto:

### Informatica e Sviluppo Software:
- **Sviluppo Web**: La creazione e la gestione del sito web NewS coinvolgono lo sviluppo di applicazioni web utilizzando linguaggi di programmazione come HTML, CSS, JavaScript e PHP.
- **Web Scraping**: Utilizzando la libreria di automazione web Selenium in C#, è possibile estrarre informazioni da fonti come il feed RSS della Gazzetta per integrarle nel sito NewS.
- **Gestione del Database**: È necessario progettare e implementare un database per archiviare e gestire articoli, utenti e altre informazioni pertinenti.
- **Sicurezza Informatica**: Implementare misure di sicurezza per proteggere i dati degli utenti, prevenire attacchi informatici e garantire la privacy delle informazioni personali.

### Design e User Experience (UX):
- **Progettazione dell'Interfaccia Utente (UI)**: Il design dell'interfaccia utente del sito NewS include la disposizione degli elementi visivi, la scelta dei colori, dei caratteri e delle icone per creare un'esperienza visiva piacevole e intuitiva.
- **Usabilità e Accessibilità**: Si lavora per rendere il sito NewS facilmente accessibile a tutti gli utenti, compresi coloro con disabilità, attraverso un design responsive e l'implementazione di pratiche di accessibilità web.
- **User Feedback e Testing**: Vengono raccolti feedback dagli utenti e condotti test di usabilità per valutare l'esperienza complessiva degli utenti e apportare eventuali miglioramenti all'interfaccia utente.

### Economia e Business:
- **Modello di Business**: È necessario definire un modello di business sostenibile per il progetto NewS, che potrebbe includere entrate pubblicitarie, abbonamenti a pagamento o altri flussi di reddito.
- **Marketing e Pubblicità**: Sviluppare strategie di marketing per promuovere il sito NewS e attirare un pubblico più ampio attraverso social media, annunci online e partnership con altre piattaforme.
- **Analisi dei Dati e Monitoraggio delle Prestazioni**: Utilizzare strumenti di analisi web per monitorare le prestazioni del sito, analizzare il comportamento degli utenti e adattare le strategie di business in base ai risultati ottenuti.


# Work Breakdown Structure (WBS)
### Work Breakdown Structure (WBS)

1. **Sviluppo del Sito Web**
   - 1.1 Progettazione dell'Interfaccia Utente (UI)
   - 1.2 Implementazione del Layout e dei Componenti Web
   - 1.3 Integrazione dei Moduli Funzionali
     - 1.3.1 Login e Registrazione
     - 1.3.2 Ricerca e Navigazione
     - 1.3.3 Visualizzazione degli Articoli
     - 1.3.4 Commenti e Feedback degli Utenti
   - 1.4 Ottimizzazione per Dispositivi Mobili
   - 1.5 Test e Debugging

2. **Web Scraping e Integrazione con Feed RSS**
   - 2.1 Analisi dei Requisiti per il Web Scraping
   - 2.2 Implementazione dello Scraping in Selenium (C#)
   - 2.3 Estrazione e Elaborazione dei Dati RSS dalla Gazzetta
   - 2.4 Integrazione dei Dati nell'Applicazione Web

3. **Gestione dei Contenuti e Database**
   - 3.1 Progettazione del Database per gli Articoli e i Commenti
   - 3.2 Implementazione delle Funzionalità CRUD per il Contenuto
   - 3.3 Gestione degli Utenti e dei loro Dati
   - 3.4 Sicurezza e Protezione dei Dati

4. **Deployment e Manutenzione**
   - 4.1 Preparazione dell'Ambiente di Hosting
   - 4.2 Deploy dell'Applicazione Web sul Server
   - 4.3 Monitoraggio delle Prestazioni e Manutenzione
   - 4.4 Aggiornamenti e Miglioramenti Continui

5. **Gestione del Progetto**
   - 5.1 Pianificazione e Scheduling delle Attività
   - 5.2 Monitoraggio del Progresso e Risorse
   - 5.3 Gestione dei Rischi e Risoluzione dei Problemi





# Matrice Rischi 

| #   | Tipo di Rischio                 | Descrizione                                       | Probabilità | Impatto | Livello di Rischio | Azioni Preventive                                    |
|-----|--------------------------------|---------------------------------------------------|-------------|---------|--------------------|------------------------------------------------------|
| 1   | Ritardo nello sviluppo         | Difficoltà nell'integrazione di componenti esterni | Alta        | Alto    | Alto               | Pianificare con margini di tempo aggiuntivi          |
| 2   | Problemi di sicurezza          | Vulnerabilità del sistema a attacchi informatici  | Media       | Alto    | Medio              | Implementare procedure di sicurezza e crittografia   |
| 3   | Mancanza di risorse            | Insufficiente disponibilità di personale qualificato | Media    | Alto    | Medio              | Assicurarsi di avere un team adeguato e risorse sufficienti |
| 4   | Cambiamenti nei requisiti      | Modifiche richieste dal cliente durante lo sviluppo | Alta        | Medio   | Medio              | Mantenere una comunicazione stretta con il cliente e documentare le modifiche |
| 5   | Problemi di hosting            | Instabilità o errori nel servizio di hosting      | Media       | Alto    | Medio              | Scegliere un provider di hosting affidabile e monitorare regolarmente le prestazioni |
| 6   | Perdita di dati                | Mancata corretta gestione dei backup               | Media       | Alto    | Medio              | Implementare procedure regolari di backup e recupero dati |
| 7   | Difficoltà nell'integrazione  | Incompatibilità tra i diversi moduli dell'applicazione | Alta     | Medio   | Medio              | Effettuare test di integrazione durante lo sviluppo   |
| 8   | Problemi di compatibilità      | Incompatibilità tra diversi browser o dispositivi | Media       | Medio   | Medio              | Effettuare test di compatibilità su piattaforme diverse |
| 9   | Scarsa adozione dell'applicazione | Bassa interesse o utilizzo da parte degli utenti | Media      | Alto    | Medio              | Coinvolgere gli utenti durante lo sviluppo e fornire un'interfaccia intuitiva |
| 10  | Problemi legali                | Violazione di copyright o normative sulla privacy | Bassa       | Alto    | Medio              | Effettuare una rigorosa revisione legale dei contenuti e delle politiche di privacy |

# Project Charter

## Progetto NewS

**Codice:** P01

**Data Revisione:** 21/04/2024

---

## Scopo del progetto e del prodotto:

Il progetto NewS mira a sviluppare un'applicazione web per gli appassionati di calcio, denominata NewS, che fornisca un'esperienza completa e personalizzata per l'accesso a notizie, aggiornamenti e statistiche riguardanti il mondo del calcio. Il prodotto consentirà agli utenti di visualizzare articoli, classifiche, risultati delle partite e informazioni sui giocatori provenienti da fonti affidabili.

---

## Obiettivi di progetto:

- Sviluppare un'applicazione web intuitiva e facile da usare per gli appassionati di calcio.
- Integrare un sistema di web scraping per ottenere notizie e aggiornamenti dalle fonti RSS dei principali siti sportivi.
- Implementare un'interfaccia utente accattivante e responsive per una visualizzazione ottimale su diverse piattaforme (desktop, mobile).
- Assicurare la sicurezza dei dati degli utenti e proteggere l'applicazione da vulnerabilità informatiche.
- Rispettare i tempi e il budget stabiliti per il completamento del progetto.

---

## Requisiti di alto livello:

- Accesso alle notizie e agli aggiornamenti tramite feed RSS.
- Visualizzazione di articoli, classifiche, risultati delle partite e informazioni sui giocatori.
- Funzionalità di ricerca avanzata per filtrare e trovare contenuti specifici.
- Personalizzazione dell'esperienza utente con preferenze e impostazioni personalizzate.
- Integrazione con i social media per la condivisione di contenuti e interazioni sociali.

---

## Project Manager:

- **Nome:** Andrea Vismara

## Membri del team:

- **Nome:** Andrea Vismara

## Committente:

- **Nome:** Prof. Marco Grena

## Sponsor:

- Nessuno Sponsor

## Elenco degli stakeholder:<br>

- #### Utenti finali: <br>
Gli appassionati di calcio che utilizzano l'app per rimanere aggiornati sulle ultime notizie, risultati e statistiche.<br>
- #### Squadre di calcio: <br>
Le squadre di calcio potrebbero essere interessate all'app per monitorare la loro visibilità mediatica e ottenere informazioni sulle prestazioni delle altre squadre.<br>
- #### Giocatori di calcio: <br>
I giocatori professionisti e amatoriali potrebbero essere interessati a seguire le notizie relative al loro sport e alle loro squadre.<br>
- #### Allenatori: <br>
Gli allenatori potrebbero utilizzare l'app per analizzare le prestazioni delle squadre avversarie e rimanere aggiornati sulle ultime tattiche e strategie nel mondo del calcio.<br>
- #### Media e giornalisti sportivi: <br>
I media e i giornalisti sportivi potrebbero utilizzare l'app per reperire informazioni e fonti per le loro pubblicazioni e reportage.<br>
- #### Federazioni sportive: <br>
Le federazioni calcistiche nazionali e internazionali potrebbero essere interessate all'app per monitorare l'interesse e l'engagement degli appassionati di calcio.<br>
- #### Sponsor e partner commerciali: <br>
Le aziende e i marchi interessati allo sport potrebbero essere interessati a sponsorizzare l'app o a collaborare per promuovere i loro prodotti e servizi.<br>
- #### Agenzie di scommesse sportive: <br>
Le agenzie di scommesse potrebbero utilizzare l'app per ottenere informazioni aggiornate e statistiche per i loro clienti.<br>
- #### Operatori di trasmissioni sportive: <br>
Le emittenti televisive e online potrebbero utilizzare l'app per integrare le loro trasmissioni con contenuti aggiuntivi e aggiornamenti in tempo reale.<br>
- #### Organizzatori di eventi sportivi: <br>
Gli organizzatori di eventi sportivi potrebbero utilizzare l'app per promuovere i loro eventi e fornire informazioni ai partecipanti.<br>

---

## Tempistica preliminare - GANTT di alto livello:

### Diagramma di Gantt
|-----------------------------------|-----------------------------------|-----------------------------------|
|           Fase del Progetto       |              Durata               |              Responsabile         |
|-----------------------------------|-----------------------------------|-----------------------------------|
| Sviluppo del Sito Web             | 4 Settimane                       | Team di Sviluppo Web              |
|-----------------------------------|-----------------------------------|-----------------------------------|
| Web Scraping e Integrazione      | 2 Settimane                       | Team di Sviluppo Web              |
| dei Contenuti                     |                                   |                                   |
|-----------------------------------|-----------------------------------|-----------------------------------|
| Gestione del Database             | 3 Settimane                       | Team di Sviluppo Web              |
|-----------------------------------|-----------------------------------|-----------------------------------|
| Sicurezza e Privacy               | 1 Settimana                       | Team di Sicurezza Informatica     |
|-----------------------------------|-----------------------------------|-----------------------------------|
| Design e Usabilità                | 2 Settimane                       | Team di Design e UX               |
|-----------------------------------|-----------------------------------|-----------------------------------|
| Business e Marketing              | 2 Settimane                       | Team di Marketing e Business      |
|-----------------------------------|-----------------------------------|-----------------------------------|
| Test e Lancio del Sito            | 1 Settimana                       | Team di Sviluppo Web              |
|-----------------------------------|-----------------------------------|-----------------------------------|

## Prodotti principali - deliverables:

- Specifiche del progetto
- Design dell'interfaccia utente
- Codice sorgente dell'applicazione
- Documentazione tecnica
- Test di accettazione e di sistema
- Applicazione web NewS

## Schedulazione delle milestones:

- **Data Consegna:** [22/04/2024]

---

## Budget di massima:

- **Totale Budget:** [0]

---

## Rischi di alto livello:

- Possibili ritardi nello sviluppo del software
- Problemi di compatibilità con i diversi browser e dispositivi
- Sicurezza informatica e protezione dei dati degli utenti
- Variazioni nei requisiti del progetto durante lo sviluppo

---

## Approvazioni:

**Nome del Project Manager:** Andrea Vismara  
**Nome del Committente:** Prof. Marco Grena

**Firma del Project Manager:** Andrea Vismaara 
**Firma del Committente:** Prof. Marco Grena

**Luogo, data:** Bergamo 22/04/2024



In conclusione, il progetto NewS rappresenta un'interessante fusione di competenze e conoscenze provenienti da diverse discipline, che collaborano per creare un'esperienza digitale completa e di alta qualità per gli utenti. La sinergia tra informatica, design e business è essenziale per il successo e la sostenibilità del progetto.
