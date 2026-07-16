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
| Tramontana-B | 39,2 | +19,2 | 48 | 0 | 🟢 |
| Scirocco-B | 27,9 | +7,9 | 28 | 0 | 🟢 |
| Maestrale-B | 25,2 | +5,2 | 50 | 0 | 🟢 |
| Zefiro | 24,2 | +4,2 | 41 | 0 | 🟢 |
| Grecale | 20,0 | -0,0 | 48 | 0 | 🟢 |
| Libeccio | 19,6 | -0,4 | 48 | 0 | 🟢 |
| Zefiro-B | 15,5 | -4,5 | 30 | 0 | 🟢 |
| Ponente | 14,8 | -5,2 | 48 | 0 | ⏸ |
| Libeccio-B | 13,7 | -6,3 | 38 | 0 | 🟢 |
| Maestrale | 12,6 | -7,4 | 51 | 0 | 🟢 |
| Grecale-B | 6,8 | -13,2 | 43 | 2 | 🟢 |
| Scirocco | 6,4 | -13,6 | 46 | 1 | ⏸ |
| Ponente-B | 6,4 | -13,6 | 37 | 2 | 🟢 |
| Tramontana | 0,0 | -20,3 | 45 | 4 | 🛑 |

_Aggiornato: 16/07 20:41_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
