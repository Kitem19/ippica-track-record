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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=6b1d85e2)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=ad29c367)

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

- **Scirocco**: dati ridotti avanti di 16,9u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 11,3u — qui gli extra non aiutano
- **Libeccio**: in sostanziale pareggio — troppo presto per dire
- **Tramontana**: dati ridotti avanti di 33,8u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 4,6u
- **Zefiro**: in sostanziale pareggio — troppo presto per dire
- **Ponente**: in sostanziale pareggio — troppo presto per dire

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 33,5 | +13,5 | 92 | 0 | 🟢 |
| Scirocco-B | 16,8 | -3,2 | 53 | 0 | 🟢 |
| Maestrale-B | 13,7 | -6,3 | 74 | 14 | ⏸ |
| Libeccio-B | 12,6 | -7,4 | 70 | 2 | 🟢 |
| Zefiro | 11,7 | -8,3 | 72 | 0 | ⏸ |
| Zefiro-B | 11,2 | -8,8 | 53 | 0 | 🟢 |
| Libeccio | 10,6 | -9,4 | 73 | 21 | ⏸ |
| Grecale | 10,2 | -9,8 | 86 | 3 | 🟢 |
| Grecale-B | 5,6 | -14,4 | 79 | 2 | 🟢 |
| Ponente-B | 5,5 | -14,5 | 49 | 2 | 🟢 |
| Ponente | 4,0 | -16,0 | 62 | 6 | ⏸ |
| Maestrale | 2,4 | -17,6 | 99 | 0 | 🟢 |
| Scirocco | 0,0 | -20,1 | 80 | 8 | 🛑 |
| Tramontana | 0,0 | -20,3 | 45 | 48 | 🛑 |

_Aggiornato: 17/07 21:21_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
