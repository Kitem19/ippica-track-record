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

![Coppie: dati completi vs ridotti](charts/equity_pairs.png)

![Delta per coppia](charts/coppie_delta.png)
## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Libeccio | 28,2 | +8,2 | 15 | 0 | 🟢 |
| Scirocco-B | 25,1 | +5,1 | 10 | 0 | 🟢 |
| Zefiro | 22,3 | +2,3 | 14 | 0 | 🟢 |
| Grecale | 21,7 | +1,7 | 16 | 0 | 🟢 |
| Libeccio-B | 21,3 | +1,3 | 11 | 0 | 🟢 |
| Tramontana-B | 20,0 | +0,0 | 15 | 0 | 🟢 |
| Maestrale-B | 19,6 | -0,4 | 15 | 0 | 🟢 |
| Ponente | 19,4 | -0,6 | 17 | 0 | 🟢 |
| Grecale-B | 15,5 | -4,5 | 12 | 0 | 🟢 |
| Zefiro-B | 15,3 | -4,7 | 10 | 0 | 🟢 |
| Maestrale | 15,2 | -4,8 | 16 | 0 | 🟢 |
| Scirocco | 14,0 | -6,0 | 15 | 0 | 🟢 |
| Ponente-B | 13,8 | -6,2 | 15 | 0 | 🟢 |
| Tramontana | 10,7 | -9,3 | 15 | 0 | 🟢 |

_Aggiornato: 15/07 18:36_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
