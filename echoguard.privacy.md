# PRIVACY POLICY DI ECHOGUARD

## Ultimo aggiornamento: 23/06/2026

Questa Privacy Policy descrive come EchoGuard, sviluppato da EchoStudio, tratta i dati personali nell'ambito delle attività di moderazione automatica. Si applica ai membri dei server in cui EchoGuard è attivo e agli amministratori che lo configurano. Utilizzando il Bot, o restando in un server in cui è attivo, prendi atto del trattamento descritto di seguito.


## 1. TITOLARE DEL TRATTAMENTO

Il titolare del trattamento dei dati raccolti tramite EchoGuard è EchoStudio.
Per qualsiasi richiesta relativa ai dati: https://discord.gg/XAZ4EMD9vN

L'amministratore che installa e configura EchoGuard nel proprio server è responsabile di informare i membri dell'uso del Bot e di assicurare una base giuridica adeguata per la moderazione del proprio server.


## 2. DATI TRATTATI E CONSERVAZIONE

EchoGuard tratta solo i dati necessari al funzionamento della moderazione:

- ID utente Discord + storico flag/warn: per la tracciabilità delle infrazioni per utente. Conservazione: finché EchoGuard è attivo per quel server o fino a richiesta di cancellazione.
- Configurazioni del server (soglie, regole, canali di log): per personalizzare la moderazione. Conservazione: finché il Bot è presente nel server.

Messaggi analizzati: il contenuto dei messaggi viene elaborato in tempo reale per la sola finalità di analisi. EchoStudio NON conserva il testo dei messaggi dopo l'analisi.


## 3. FINALITÀ E BASE GIURIDICA (GDPR)

- Finalità: fornire funzionalità di moderazione automatica e contribuire alla sicurezza dei server.
- Base giuridica (art. 6 GDPR): il legittimo interesse del titolare e dell'amministratore del server a mantenere un ambiente sicuro e conforme alle regole della community.


## 4. COME FUNZIONA L'ANALISI (PIPELINE)

L'analisi avviene in due fasi:

1) Filtro regex locale: un primo controllo basato su espressioni regolari intercetta i pattern noti SENZA inviare alcun dato a sistemi AI esterni.
2) Analisi tramite modello linguistico (LLM): solo i messaggi non risolti dal filtro vengono inviati, in tempo reale, a un modello AI. I modelli utilizzati sono Minerva-7B-instruct (Sapienza NLP, Apache 2.0) e Gemma 4 E4B (Google DeepMind, Apache 2.0), modelli open-weight eseguiti su infrastruttura Hugging Face e impiegati in modo alternato.


## 5. HOSTING DEI MODELLI AI: HUGGING FACE

I modelli linguistici di EchoGuard sono eseguiti esclusivamente su Hugging Face.

- Hugging Face, Inc. ha sede negli Stati Uniti; il suo stabilimento principale nell'UE è Hugging Face SAS (Parigi, Francia), con autorità di controllo la CNIL.
- L'infrastruttura di inferenza è configurata, ove possibile, in region UE, in modo che l'elaborazione avvenga all'interno dello Spazio Economico Europeo.
- Eventuali trasferimenti di dati verso gli Stati Uniti sono disciplinati da Clausole Contrattuali Standard (SCC).
- Hugging Face è certificata SOC 2 Type 2 e mette a disposizione un Data Processing Agreement (DPA) conforme al GDPR.
- I messaggi inviati per l'inferenza sono elaborati in modo transitorio e non vengono conservati da EchoStudio.
- Privacy policy di Hugging Face: https://huggingface.co/privacy


## 6. USO DEI DATI

I dati sono utilizzati esclusivamente per fornire le funzionalità di moderazione. EchoStudio NON vende dati a terzi e NON li utilizza per finalità pubblicitarie o per l'addestramento di modelli proprietari.


## 7. CONDIVISIONE DEI DATI

I dati possono essere condivisi soltanto con: (a) Discord, in quanto piattaforma; (b) Hugging Face, ai soli fini dell'analisi in tempo reale; (c) autorità competenti, ove richiesto dalla legge applicabile.


## 8. SICUREZZA

Adottiamo misure tecniche e organizzative adeguate (es. trasmissione cifrata tramite TLS, accesso limitato ai dati) per proteggere le informazioni trattate. Nessun sistema è tuttavia sicuro al 100%.


## 9. MINORI

EchoGuard segue i Termini di Discord. Per gli utenti tra 13 e 16 anni residenti nell'UE può essere necessario il consenso di un genitore o tutore. Il Bot non è destinato a bambini di età inferiore ai 13 anni.


## 10. DIRITTI DEGLI UTENTI (GDPR)

Se risiedi nell'UE/SEE hai diritto a: accesso, rettifica, cancellazione, limitazione, portabilità e opposizione al trattamento. Puoi esercitare tali diritti contattandoci su Discord. Hai inoltre il diritto di proporre reclamo a un'autorità di controllo (in Italia, il Garante per la protezione dei dati personali).


## 11. MODIFICHE

Possiamo aggiornare questa Privacy Policy in qualsiasi momento. La data in cima al documento indica l'ultimo aggiornamento.


## 12. CONTATTI

Per domande o richieste relative ai dati: https://discord.gg/XAZ4EMD9vN
