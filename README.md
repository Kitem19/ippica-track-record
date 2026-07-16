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
| Tramontana-B | 35,1 | +15,1 | 43 | 0 | 🟢 |
| Scirocco-B | 31,9 | +11,9 | 24 | 0 | 🟢 |
| Maestrale-B | 28,9 | +8,9 | 46 | 0 | 🟢 |
| Zefiro | 27,3 | +7,3 | 36 | 0 | 🟢 |
| Grecale | 24,0 | +4,0 | 43 | 0 | 🟢 |
| Libeccio | 20,8 | +0,8 | 44 | 0 | 🟢 |
| Zefiro-B | 17,5 | -2,5 | 28 | 0 | 🟢 |
| Ponente | 17,3 | -2,7 | 44 | 0 | 🟢 |
| Libeccio-B | 16,1 | -3,9 | 33 | 0 | 🟢 |
| Maestrale | 15,2 | -4,8 | 46 | 0 | 🟢 |
| Ponente-B | 13,1 | -6,9 | 32 | 2 | 🟢 |
| Grecale-B | 12,5 | -7,5 | 38 | 2 | 🟢 |
| Scirocco | 10,2 | -9,8 | 42 | 0 | 🟢 |
| Tramontana | 0,7 | -19,3 | 44 | 0 | 🟢 |

_Aggiornato: 16/07 19:41_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
