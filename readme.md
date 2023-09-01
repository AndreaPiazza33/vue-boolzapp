# Boolzapp - a (not very) innovative messaging platform
## TRACCIA:
### Milestone 1
- Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e
dall’interlocutore (bianco) assegnando due classi CSS diverse  
- Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare
nome e immagine di ogni contatto  
### Milestone 2
- Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i
messaggi relativi al contatto attivo all’interno del pannello della conversazione  
- Click sul contatto mostra la conversazione del contatto cliccato  
### Milestone 3
- Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando
“enter” il testo viene aggiunto al thread sopra, come messaggio verde  
- Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà
un “ok” come risposta, che apparirà dopo 1 secondo.  
### Milestone 4
- Ricerca utenti: scrivendo qualcosa nell’input a sinistra, vengono visualizzati solo i
contatti il cui nome contiene le lettere inserite (es, Marco, Matteo Martina -> Scrivo
“mar” rimangono solo Marco e Martina)  
### Milestone 5 - opzionale
- Cancella messaggio: cliccando sul messaggio appare un menu a tendina che
permette di cancellare il messaggio selezionato
- Visualizzazione ora e ultimo messaggio inviato/ricevuto nella lista dei contatti
## PROCEDIMENTO:
### MILESTONE 1:
- creare la grafica base che include:
  - sfondo a colori;
  - contenitore con:
    - chat principale (messaggi ricevuti e inviati);
    - lista contatti (thumbnails).
- creare le colorazioni per i messaggi della chat;
- stampare ogni elemento della lista contatti in modo dinamico al posto degli elementi fissi.
### MILESTONE 2:
- rendere dinamici i messaggi nella chat principale;
- creare evento al click del contatto nella lista contatti:
  - rendere i contatti cliccabili;
  -  una volta cliccato recuperare il contatto esatto;
  - sostituire il contatto cliccato con quello presente nella chat principale.
### MILESTONE 3:
- creare un input testuale dove inserire il nuovo messaggio;
- collegare l'input alla chat per inviare il nuovo messaggio quando verrà digitato 'ENTER';
- assegnare le stesse caratteristiche dei messaggi già presenti a quello che deve essere inviato.
- creare una risposta(OK) ad ogni nuovo inserimento;
- assegnare le stesse caratteristiche dei messaggi già ricevuti alla risposta;
- inviare la risposta dopo un intervallo di tempo (1 secondo).
### MILESTONE 4:
- collegare l'input della ricerca alla ricerca nella lista;
- controllare il funzionamento della ricerca;
- rendere visibili i risultati durante la ricerca.
### MILESTONE 5:
- al click sul messaggio creare un evento per cui:  
  - compare un menu a tendina che permette l' eliminazione del messaggio cliccato;
- per ogni contatto nella lista recuperare ora e ultimo messaggio inviato/ricevuto;
-  stamparli a schermo nella lista contatti.

