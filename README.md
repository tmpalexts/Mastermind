# 🧩 Mastermind

Gioco **Mastermind** in una singola pagina HTML (nessuna dipendenza, funziona anche offline).

▶️ **Gioca ora** (via htmlpreview):

- dopo il merge su `main`: <https://htmlpreview.github.io/?https://raw.githubusercontent.com/tmpalexts/Mastermind/main/index.html>
- dal branch di sviluppo: <https://htmlpreview.github.io/?https://raw.githubusercontent.com/tmpalexts/Mastermind/arena/01a02fb3-mastermind/index.html>

## Regole
- Di default il codice segreto è composto da **3 cifre da 1 a 9, tutte diverse**; hai 10 tentativi.
- Dopo ogni tentativo ricevi gli indizi:
  - 🟢 **pallino verde pieno** → simbolo giusto **al posto giusto**
  - 🟡 **pallino giallo vuoto** → simbolo giusto ma **al posto sbagliato**
  - ⚪ **pallino grigio** → simbolo **assente** dal codice
- I pallini indicano solo *quanti* simboli sono corretti, non *quali*.

## Impostazioni
- **Simboli**: cifre (1–9) oppure **6 colori** ben distinguibili
- **Lunghezza codice**: 3, 4 o 5
- **Simboli ripetuti**: attivabili (es. 2 · 2 · 1)
- **Tentativi**: 8, 10, 12 o illimitati

Partita, impostazioni e statistiche vengono salvate automaticamente nel browser (localStorage). Su computer si può giocare anche con la tastiera: cifre, ⌫ e Invio.
