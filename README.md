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
| Scirocco-B | 34,3 | +14,3 | 14 | 0 | 🟢 |
| Tramontana-B | 32,3 | +12,3 | 29 | 0 | 🟢 |
| Libeccio | 29,9 | +9,9 | 32 | 0 | 🟢 |
| Grecale | 25,3 | +5,3 | 30 | 0 | 🟢 |
| Zefiro | 24,4 | +4,4 | 24 | 0 | 🟢 |
| Maestrale-B | 22,8 | +2,8 | 31 | 0 | 🟢 |
| Libeccio-B | 21,9 | +1,9 | 23 | 0 | 🟢 |
| Ponente | 20,0 | +0,0 | 33 | 0 | 🟢 |
| Scirocco | 15,1 | -4,9 | 28 | 0 | 🟢 |
| Maestrale | 14,3 | -5,7 | 30 | 0 | 🟢 |
| Zefiro-B | 12,1 | -7,9 | 17 | 0 | 🟢 |
| Grecale-B | 8,1 | -11,9 | 23 | 2 | 🟢 |
| Ponente-B | 8,1 | -11,9 | 23 | 2 | 🟢 |
| Tramontana | 7,4 | -12,6 | 29 | 0 | 🟢 |

_Aggiornato: 16/07 16:11_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
