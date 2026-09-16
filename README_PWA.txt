# M.IV Calendria — PWA

Versione mobile installabile della V22.1 stabile.

## Cosa offre
- stessa logica di pianificazione della V22.1;
- importazione Excel direttamente nel browser (XLSX/XLSM);
- calendari e sessioni salvati localmente nel browser;
- modifica/blocco/rigenerazione;
- controllo finale;
- griglia responsive per telefono e tablet;
- esportazione Excel direttamente dal dispositivo;
- esportazione PDF tramite la finestra di stampa del dispositivo;
- installazione come app con icona M.IV Calendria.

## Installazione
La PWA deve essere servita da un indirizzo HTTPS (oppure da localhost durante i test). Non aprire index.html con doppio clic: i browser non consentono normalmente service worker e installazione PWA da file://.

Per un utilizzo reale consigliato: pubblicare questa cartella su un piccolo hosting statico HTTPS (GitHub Pages, Netlify, server web dell'Istituto, ecc.). I dati Excel e i calendari vengono elaborati/salvati localmente nel browser; non è previsto un backend per i dati scolastici.

Su iPhone/iPad: Safari → Condividi → Aggiungi alla schermata Home.
Su Android: menu del browser → Installa app / Aggiungi alla schermata Home.
Su desktop: usare l'icona di installazione del browser quando disponibile.
