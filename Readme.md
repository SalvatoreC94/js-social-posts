# Social Posts

Questo progetto ha lo scopo di creare un feed social dinamico utilizzando JavaScript per gestire i post, i like, e altre funzionalità interattive.

## Descrizione

Il progetto si divide in diverse milestone che coprono le varie funzionalità da implementare.

### Milestone 1

Creiamo un array di oggetti che rappresentano ciascun post. Ogni post dovrà contenere le seguenti informazioni:

- `id`: numero progressivo da 1 a n
- `nome autore`
- `foto autore`
- `data`: in formato americano (mm-gg-yyyy)
- `testo del post`
- `immagine` (non tutti i post devono avere un'immagine)
- `numero di likes`

Le immagini possono essere ottenute da un servizio di placeholder, come ad esempio [Unsplash](https://unsplash.it/300/300?image=<id>).

### Milestone 2

Stampiamo i post del nostro feed prendendo come riferimento il layout di esempio presente nell'HTML.

### Milestone 3

Aggiungiamo l'interattività:

- Se clicchiamo sul tasto **"Mi Piace"**, il testo del bottone cambia colore.
- Il numero di like viene incrementato.
- Gli id dei post ai quali è stato messo un like vengono salvati in un secondo array.

### Bonus

1. **Formattare le date** in formato italiano (gg/mm/aaaa).
2. **Gestire l'assenza dell'immagine profilo** con un elemento di fallback che mostra le iniziali dell'utente (es. "Luca Formicola" → "LF").
3. **Gestire il doppio click sul tasto "Mi Piace"**: se abbiamo già cliccato il like, il contatore viene decrementato e il colore del bottone torna allo stato originale.

## Consigli

- Ragioniamo passo passo: prima definiamo la logica in italiano, poi la traduciamo in codice.
- Utilizziamo `console.log()` per verificare i dati e il funzionamento del codice.
- Suddividiamo il codice in funzioni più piccole e riutilizzabili, dove possibile.
