# animate-url

Una semplice pagina web che anima l'URL, il titolo della pagina e il contenuto utilizzando una sequenza di emoji. Questo repository utilizza `Favico.js` per animare l'icona del sito (favicon), offrendo un modo interattivo e divertente per migliorare l'esperienza utente sul tuo sito web.

## Funzionalità

- **Animazione Emoji nell'URL**: L'URL nella barra degli indirizzi del browser viene animato con una sequenza di emoji.
- **Animazione del Titolo**: Il titolo della pagina cambia continuamente con una serie di emoji.
- **Animazione del Contenuto**: Il contenuto della pagina (all'interno di un div specifico) cambia in tempo reale con emoji diverse.
- **Emoji Personalizzabili**: È possibile modificare facilmente o estendere la lista di emoji a proprio piacimento.

## Installazione

Per utilizzare questa animazione nel tuo sito web, basta copiare il codice HTML nel tuo progetto. La pagina utilizza collegamenti CDN esterni per le librerie come `Favico.js` e Google Fonts (Poppins).

1. Clona o scarica questo repository:
   ```bash
   git clone https://github.com/masonedotlcoud/animate-url.git
   ```
2. Apri il file `index.html` in un browser per vedere l'animazione in azione.

## Utilizzo

1. **Animazione dell'URL**: L'URL nella barra degli indirizzi del browser cambia dinamicamente con l'animazione delle emoji.
2. **Animazione del Titolo**: Il titolo della pagina cambierà continuamente con diverse emoji, creando un effetto di animazione.
3. **Animazione del Contenuto**: Il contenuto al centro della pagina mostrerà una nuova emoji ogni 70ms, creando una visualizzazione di emoji in tempo reale.

Per avviare le animazioni, la pagina include uno script JavaScript che modifica l'URL, il titolo e il contenuto utilizzando funzioni `setTimeout`.

## Personalizzazione

- **Modifica le Emoji**: Modifica l'array `myEmojis` nello script per includere le emoji che desideri visualizzare.
- **Regola la Velocità**: Puoi cambiare la velocità dell'animazione modificando il valore `70` all'interno delle funzioni `setTimeout`.

## Licenza

Questo progetto è distribuito sotto la Licenza MIT - vedi il file [LICENSE](LICENSE) per ulteriori dettagli.


## Autore

Questo progetto è stato creato da [alessandromasone](https://github.com/alessandromasone).