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
| Tramontana-B | 36,2 | +16,2 | 46 | 0 | 🟢 |
| Scirocco-B | 29,9 | +9,9 | 26 | 0 | 🟢 |
| Maestrale-B | 26,2 | +6,2 | 48 | 0 | 🟢 |
| Zefiro | 24,3 | +4,3 | 39 | 0 | 🟢 |
| Libeccio | 20,6 | +0,6 | 47 | 0 | 🟢 |
| Grecale | 20,1 | +0,1 | 46 | 0 | 🟢 |
| Ponente | 16,8 | -3,2 | 46 | 0 | 🟢 |
| Zefiro-B | 16,5 | -3,5 | 29 | 0 | 🟢 |
| Libeccio-B | 15,7 | -4,3 | 36 | 0 | 🟢 |
| Maestrale | 12,7 | -7,3 | 49 | 0 | 🟢 |
| Ponente-B | 9,4 | -10,6 | 35 | 2 | 🟢 |
| Grecale-B | 8,8 | -11,2 | 41 | 2 | 🟢 |
| Scirocco | 7,4 | -12,6 | 45 | 0 | 🟢 |
| Tramontana | 0,0 | -20,3 | 45 | 2 | 🛑 |

_Aggiornato: 16/07 20:21_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
