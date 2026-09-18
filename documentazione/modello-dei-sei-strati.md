# Modello dei sei strati

## Premessa

L'architettura descrive l'impresa come un sistema di sei strati collegati. La trasformazione agentica non elimina gli strati esistenti: cambia il modo in cui comunicano, espone capacità controllate agli agenti AI e riduce la distanza tra intento aziendale ed esecuzione operativa.

## Strato 1 — Prodotti dati e conoscenza

I dati devono essere comprensibili, governati e accompagnati dal contesto necessario per interpretarli. Ogni prodotto dati dovrebbe dichiarare proprietario, significato, qualità attesa, frequenza di aggiornamento, classificazione e condizioni d'uso.

Gli agenti possono recuperare soltanto le informazioni compatibili con l'identità dell'utente, lo scopo dichiarato e le regole di accesso.

## Strato 2 — Livello semantico e strumenti

Questo strato traduce il linguaggio aziendale in operazioni tecniche verificabili. Contiene metriche condivise, definizioni, contratti degli strumenti, controlli di autorizzazione e regole di validazione.

Il codice SQL continua a esistere, ma diventa un dettaglio implementativo protetto. L'utente domanda “quale fatturato è a rischio?”, non “quale tabella devo interrogare?”.

## Strato 3 — ERP come sistema di registrazione e azione

L'ERP conserva il ruolo di fonte ufficiale delle transazioni. Gli agenti leggono e preparano operazioni tramite interfacce dichiarate. Le modifiche devono rispettare le stesse regole applicate agli utenti e ai sistemi tradizionali.

Le azioni sensibili richiedono controlli preventivi, idempotenza, tracciabilità e una strategia di annullamento o compensazione.

## Strato 4 — Esperienza per intento

L'interfaccia passa dalla navigazione per schermate all'espressione dell'intento. Una buona esperienza agentica mostra risposta, fonti, ipotesi, incertezza, azioni disponibili e conseguenze previste.

La conversazione è soltanto una modalità. Servono anche code di eccezioni, aree di approvazione e viste strutturate per confrontare alternative.

## Strato 5 — Processi agentici

I processi diventano flussi osservabili nei quali persone, agenti e sistemi collaborano. Ogni passaggio deve avere un responsabile, uno stato, una scadenza, condizioni di ingresso e uscita, e una gestione esplicita delle eccezioni.

L'autonomia non è binaria: può variare dalla sola osservazione all'esecuzione entro limiti definiti.

## Strato 6 — Modello di business adattivo

Il livello strategico collega le azioni degli agenti a risultati economici misurabili. Obiettivi, priorità e limiti diventano elementi operativi del sistema, non soltanto dichiarazioni in un documento.

Il ciclo di feedback permette di capire quali decisioni generano valore, dove l'automazione aumenta il rischio e quali nuove proposte di valore diventano possibili.

## Capacità trasversali

Governance, sicurezza, identità, autorizzazioni, osservabilità, audit e valutazioni attraversano tutti e sei gli strati. Non costituiscono una fase finale del progetto: devono essere progettati insieme al primo caso d'uso.

