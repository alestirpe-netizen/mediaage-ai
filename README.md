# MediaAge AI

Building AI course project — Reaktor Innovations / University of Helsinki

## Summary

MediaAge AI è un assistente conversazionale basato sull'intelligenza artificiale pensato per supportare formatori e operatori nell'alfabetizzazione digitale di anziani e persone fragili. Il sistema genera spiegazioni semplificate, risponde alle domande frequenti in linguaggio accessibile e adatta i contenuti formativi al livello di ciascun utente.

## Background

### Quale problema risolve?

In Italia, una larga parte della popolazione anziana e delle fasce fragili incontra gravi difficoltà nell'utilizzo degli strumenti digitali di base: servizi online della pubblica amministrazione, home banking, comunicazioni via smartphone, accesso alle informazioni sanitarie. Questo divario digitale non è soltanto un ostacolo pratico, ma una forma concreta di esclusione sociale.

I formatori che lavorano in questo settore — come quelli impegnati nei progetti DIGITALMENTIS e negli Sportelli del Consumatore — affrontano ogni giorno sfide enormi:

* ogni partecipante ha un livello di partenza diverso e un ritmo di apprendimento proprio
* le domande si ripetono spesso ma richiedono risposte sempre personalizzate
* il tempo dedicabile a ciascuna persona è inevitabilmente limitato

### Quanto è diffuso il problema?

Secondo i dati ISTAT, oltre il 40% degli italiani over 65 non utilizza internet. Tra le persone con bassa scolarizzazione o in condizioni di fragilità sociale, il dato è ancora più alto. Si tratta di milioni di persone escluse dai servizi digitali di base.

### Motivazione personale

Ho lavorato per anni come formatore nell'ambito dell'alfabetizzazione digitale, in progetti come DIGITALMENTIS 1 e 2 promossi da Assoconfam APS con il supporto del Ministero delle Imprese e del Made in Italy. Ho potuto osservare direttamente quanto sia preziosa — e quanto scarseggi — la capacità di adattare il linguaggio e il ritmo alle esigenze di ogni singola persona. MediaAge AI nasce da questa esperienza concreta.

## How is it used?

MediaAge AI si inserisce nel contesto delle attività formative rivolte ad anziani e persone fragili, affiancando (non sostituendo) il formatore umano.

**Chi lo usa:**
- Formatori e operatori degli sportelli digitali
- Associazioni di volontariato e del terzo settore
- Enti pubblici e municipalità impegnate nella riduzione del divario digitale

**Come funziona nella pratica:**

1. Il formatore o l'operatore inserisce la domanda o il tema del momento (es. "come si manda un'email", "come si accede allo SPID")
2. L'AI genera una spiegazione in linguaggio semplice, con un livello di dettaglio adattabile
3. L'AI propone piccoli esercizi o verifiche per consolidare l'apprendimento
4. Al termine della sessione, produce un breve report sulle aree di difficoltà emerse, utile per la progettazione dei moduli successivi

Il sistema può essere usato su tablet o computer durante i laboratori, oppure come strumento di preparazione per il formatore prima della lezione.

![Schema di utilizzo di MediaAge AI](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Tablet_computer_with_keyboard.jpg/640px-Tablet_computer_with_keyboard.jpg)

## Data sources and AI methods

### Fonti dei dati

| Fonte | Descrizione |
|-------|-------------|
| Materiali formativi DIGITALMENTIS | Moduli didattici già sviluppati e testati sul campo |
| FAQ degli Sportelli del Consumatore | Domande reali raccolte dagli operatori di sportello |
| Dataset pubblici ISTAT | Dati sull'uso di internet e il divario digitale in Italia |
| Input diretti dei formatori | Domande e situazioni raccolte durante le sessioni formative |

### Tecniche AI utilizzate

- **Natural Language Processing (NLP):** per comprendere le domande degli utenti e generare risposte in linguaggio semplice e accessibile
- **Modelli linguistici di grandi dimensioni (LLM):** come base per la generazione di spiegazioni adattive
- **Adaptive learning:** per calibrare il livello di difficoltà delle spiegazioni e degli esercizi in base alle risposte dell'utente
- **Text simplification:** tecniche specifiche per ridurre la complessità sintattica e lessicale dei contenuti

## Challenges

MediaAge AI non è una soluzione universale. È importante essere chiari sui suoi limiti:

- **Non sostituisce il contatto umano:** la relazione tra formatore e partecipante è un elemento fondamentale dell'apprendimento, soprattutto con le fasce fragili. L'AI può supportare, non rimpiazzare.
- **Rischio di over-semplificazione:** trovare il giusto equilibrio tra semplicità e completezza è una sfida continua. Un linguaggio troppo elementare può risultare infantilizzante.
- **Accesso alla tecnologia:** paradossalmente, uno strumento pensato per ridurre il divario digitale richiede una connessione internet e un dispositivo funzionante, che non tutti hanno.
- **Privacy e dati sensibili:** le sessioni formative coinvolgono persone fragili. È essenziale garantire che nessun dato personale venga raccolto o conservato.
- **Bias linguistici e culturali:** i modelli linguistici possono riflettere bias presenti nei dati di addestramento, con il rischio di generare contenuti inadeguati per specifici contesti culturali o territoriali.

## What next?

Il progetto potrebbe crescere in diverse direzioni:

- **Versione multimodale:** integrare supporto audio e video per utenti con difficoltà di lettura o problemi visivi
- **App dedicata per operatori:** un'interfaccia semplice e intuitiva per gli sportelli digitali territoriali
- **Modulo per le scuole:** adattare il sistema per i programmi di educazione digitale nelle scuole secondarie
- **Integrazione con i servizi pubblici:** sviluppare moduli specifici per l'accesso ai servizi INPS, SSN, SPID, CIE
- **Rete di formatori:** creare una community dove i formatori possano condividere domande, esercizi e materiali generati con l'AI

Per realizzare questi sviluppi sarebbe utile collaborare con esperti di UX per utenti anziani, sviluppatori specializzati in NLP in italiano, e partner istituzionali come Comuni, ASL e Ministeri.

## Acknowledgments

* Il progetto trae ispirazione diretta dalle attività di formazione svolte nell'ambito di **DIGITALMENTIS 1 e 2** — Assoconfam APS, con il supporto del Ministero delle Imprese e del Made in Italy e della Regione Lazio.
* Ringraziamento a tutti i cittadini over 65 e alle persone fragili incontrate durante i laboratori: le loro domande, le loro difficoltà e la loro voglia di imparare sono la vera origine di questa idea.
* Corso **Building AI** — Reaktor Innovations e Università di Helsinki.
* Corso **AI and Machine Learning** — Google Coursera Plus.
* Immagine tablet: [Tablet computer with keyboard](https://commons.wikimedia.org/wiki/File:Tablet_computer_with_keyboard.jpg) — Wikimedia Commons / CC BY-SA 3.0

