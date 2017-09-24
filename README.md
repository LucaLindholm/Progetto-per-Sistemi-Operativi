# Progetto-per-Sistemi-Operativi
Progetto per Sistemi Operativi / Corso di Ingegneria Informatica - Università degli Studi di Roma "La Sapienza"
## Descrizione
Sistema di un elenco telefonico che usa la tecnologia Windows NT e C, provvisto di applicazione client e server.
Sono implementate le seguenti funzioni:

- Aggiunta di un record all'elenco telefonico
- Rimozione di un record all'elenco telefonico
- Ricerca di un record all'elenco telefonico

## Caratteristiche

#### *Banca dati* 
L'elenco telefonico viene implementato come un insieme di record: ogni record è una *struct* che contiene un array di char per memorizzare il nome e un altro array di char per memorizzare il numero.
L'elenco degli utenti autorizzati ad aggiungere, ricercare e rimuovere un record dall'elenco telefonico, è implementato come un insieme di *struct* "Utente" così composta: un array di char per memorizzare il nome dell'utente, un valore BOOL per indicare l'autorizzazione all'aggiunta di un record, un altro per l'autorizzazione alla sua ricerca e un altro ancora per la rimozione.
