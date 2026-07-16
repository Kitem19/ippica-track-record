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
| Tramontana-B | 35,4 | +15,4 | 32 | 0 | 🟢 |
| Scirocco-B | 35,1 | +15,1 | 17 | 0 | 🟢 |
| Libeccio | 26,9 | +6,9 | 35 | 0 | 🟢 |
| Maestrale-B | 26,1 | +6,1 | 35 | 0 | 🟢 |
| Grecale | 25,1 | +5,1 | 34 | 0 | 🟢 |
| Libeccio-B | 25,1 | +5,1 | 24 | 0 | 🟢 |
| Zefiro | 23,4 | +3,4 | 27 | 0 | 🟢 |
| Zefiro-B | 22,7 | +2,7 | 20 | 0 | 🟢 |
| Ponente | 19,0 | -1,0 | 36 | 0 | 🟢 |
| Maestrale | 14,2 | -5,8 | 34 | 0 | 🟢 |
| Grecale-B | 11,6 | -8,4 | 27 | 2 | 🟢 |
| Scirocco | 11,1 | -8,9 | 31 | 0 | 🟢 |
| Ponente-B | 10,3 | -9,7 | 25 | 2 | 🟢 |
| Tramontana | 4,4 | -15,6 | 32 | 0 | 🟢 |

_Aggiornato: 16/07 17:11_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
