# Track record — corse ippiche UK/IRE

Registro pubblico e verificabile delle selezioni di **14 sistemi automatici**
(7 coppie), fase dal **15 al 31 luglio 2026**. Tutto in unità (u): nessun
importo reale.

## Come funziona la verifica

1. **Prima delle corse** pubblichiamo qui l'hash del file selezioni,
   timbrato con [OpenTimestamps](https://opentimestamps.org) sulla blockchain
   Bitcoin (`picks/*.json.ots` + `picks/hashes.txt`). Le selezioni restano
   segrete fino a fine fase.
2. **A fine fase** i file `picks/*.json` vengono pubblicati in chiaro:
   chiunque può ricalcolare l'hash (`sha256sum`) e verificare col timestamp
   (`ots verify <file>.ots`) che esistevano PRIMA delle corse.
3. Grafici e classifica si aggiornano automaticamente.

## Regole del gioco (uguali per tutti i sistemi)

- Posta fissa **1u** per selezione; LAY con **liability massima 2u** (oltre
  quota 3.00 la posta si riduce per non superare il cap).
- Cassa iniziale **20u** per sistema.
- **Stop giornaliero −10u**: le selezioni successive della giornata non
  contano nel conteggio ufficiale; si riparte l'indomani.
- **Stop di fase −20u**: definitivo, il sistema si ferma.
- P/L netto di commissione exchange 6,5%, quote snapshot al momento della
  selezione (mercato WIN, corse UK/IRE).

## I sistemi

7 coppie: ogni sistema esiste in due varianti — **nome pieno** (dati completi)
e **nome-B** (dati ridotti). Stesso motore decisionale, meno informazioni in
ingresso: l'esperimento misura quanto valgono i dati extra.

Una delle 14 serie è giocata con **denaro reale** (stesse regole, stessa
scala in unità). Non indichiamo quale.

## Grafici

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=d2c09abd)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=a29a3e2a)

### Come leggere i grafici

- **Asse verticale:** cassa in **unità** (u). Ogni sistema parte da **20u**;
  sopra 20u è in utile, sotto è in perdita.
- **Asse orizzontale:** le giocate nel tempo (una tacca per selezione).
- **Blu** = versione a **dati completi**; **arancione (-B)** = **dati ridotti**.
  Nel singolo riquadro il confronto è l'esperimento: blu sopra = i dati extra
  aiutano; arancione sopra = non aiutano (o danneggiano).
- **Riferimenti:** 20u = pari; stop giornaliero a 10u; stop di fase a 0u (fermo).
- **Attenzione:** poche giornate = **rumore**, non un trend. Le conclusioni si
  traggono a fine fase (31/7).
## Come vanno le coppie

_Poche giornate: numeri ancora rumorosi, si conclude a fine fase (31/7)._

- **Scirocco**: dati ridotti avanti di 18,6u — qui gli extra non aiutano
- **Maestrale**: in sostanziale pareggio — troppo presto per dire
- **Libeccio**: in sostanziale pareggio — troppo presto per dire
- **Tramontana**: dati ridotti avanti di 14,3u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 13,4u
- **Zefiro**: dati completi avanti di 21,5u
- **Ponente**: dati completi avanti di 6,9u

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Zefiro | 21,0 | +1,0 | 231 | 5 | 🟢 |
| Scirocco-B | 18,5 | -1,5 | 195 | 0 | 🟢 |
| Tramontana-B | 14,0 | -6,0 | 288 | 0 | 🟢 |
| Grecale | 13,2 | -6,8 | 262 | 4 | 🟢 |
| Ponente | 5,9 | -14,1 | 178 | 28 | 🟢 |
| Maestrale-B | 0,0 | -20,0 | 100 | 188 | 🛑 |
| Scirocco | 0,0 | -20,1 | 80 | 202 | 🛑 |
| Grecale-B | 0,0 | -20,2 | 137 | 131 | 🛑 |
| Tramontana | 0,0 | -20,3 | 45 | 261 | 🛑 |
| Zefiro-B | 0,0 | -20,5 | 143 | 40 | 🛑 |
| Maestrale | 0,0 | -20,5 | 104 | 209 | 🛑 |
| Libeccio | 0,0 | -20,6 | 181 | 118 | 🛑 |
| Libeccio-B | 0,0 | -20,9 | 119 | 134 | 🛑 |
| Ponente-B | 0,0 | -21,0 | 63 | 66 | 🛑 |

_Aggiornato: 24/07 19:31_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
