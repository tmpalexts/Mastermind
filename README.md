# 🧩 Mastermind

Gioco **Mastermind** in una singola pagina HTML (nessuna dipendenza, funziona anche offline).

▶️ **Gioca ora** (via htmlpreview):

- dopo il merge su `main`: <https://htmlpreview.github.io/?https://raw.githubusercontent.com/tmpalexts/Mastermind/main/index.html>
- dal branch di sviluppo: <https://htmlpreview.github.io/?https://raw.githubusercontent.com/tmpalexts/Mastermind/arena/01a0323c-mastermind/index.html>

## Novità
- 👀 **Pulsante rivela-soluzione**: ti puoi arrendere in qualsiasi momento; dopo una conferma la partita si chiude (conteggiata come persa) e il codice segreto viene mostrato in tabella e nel riquadro finale.
- 📱 **Fix layout mobile**: celle che si adattano automaticamente agli schermi più stretti (nessuno sforamento orizzontale con codici da 5 simboli), spaziature e tastierino più compatti su telefonino, zoom riabilitato.
- ⌨️ **Tastierino sempre visibile**: con molti tentativi la cronologia scorre in una propria area interna invece di spingere il pannello di input fuori schermo.
- ✨ **Grafica rinnovata**: nuova palette (viola–fucsia–azzurro), pannello e modali in vetro più morbidi, celle e pulsanti con nuovi gradienti e ombre, indizi più luminosi.

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
