# Clustering-and-explainability-on-European-Social-Survey
Progetto sviluppato per il corso Scienza ed Etica dei Dati tenutosi alla Sapienza nell'a.a. 2024/2025, volto a esplorare la delineazione di profili sociali in Europa attraverso metodi di clustering e analisi di explainability con tecniche di machine learning

## Dati
- **Fonte**: dataset ESS11 Integrated File, edition 2.0, pubblicato nel 2024 da Sikt – Norwegian Agency for Shared Services in Education and Research.
- **Ambito geografico**: 31 paesi europei, ad esempio Austria, Francia, Germania, Italia, Spagna, Svezia, Regno Unito, e molti altri.
- **Tipologia**: dati reali anonimizzati, con identificatori numerici (“idno”) e variabili generalizzate (es. regione, reddito), mentre alcune variabili personali (anno di nascita, appartenenza a minoranze) rimangono non generalizzate ma non sono identificativi.

## Obiettivo
L’obiettivo centrale è identificare profili di individui europei sulla base di:
- fiducia nelle persone e nelle istituzioni
- soddisfazione personale
- partecipazione sociale
- altri comportamenti e attitudini
Attraverso il clustering, si esplorano gruppi simili e, grazie all’uso della Random Forest e delle tecniche di explainability, si analizza quali variabili influenzano maggiormente la distinzione tra cluster.

## Possibili estensioni
- Provare altri algoritmi di clustering
- Confrontare modelli diversi per la previsione del cluster
- Incorporare dati differenti
