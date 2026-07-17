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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=51136df2)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=b204f76d)

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

- **Scirocco**: dati ridotti avanti di 18,5u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 8,1u — qui gli extra non aiutano
- **Libeccio**: in sostanziale pareggio — troppo presto per dire
- **Tramontana**: dati ridotti avanti di 41,3u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 8,9u
- **Zefiro**: dati completi avanti di 11,0u
- **Ponente**: dati completi avanti di 7,5u

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 41,0 | +21,0 | 59 | 0 | 🟢 |
| Zefiro | 28,7 | +8,7 | 50 | 0 | 🟢 |
| Scirocco-B | 27,9 | +7,9 | 35 | 0 | 🟢 |
| Maestrale-B | 22,6 | +2,6 | 62 | 0 | 🟢 |
| Grecale | 21,6 | +1,6 | 58 | 3 | 🟢 |
| Zefiro-B | 17,7 | -2,3 | 34 | 0 | 🟢 |
| Libeccio-B | 15,4 | -4,6 | 46 | 2 | 🟢 |
| Libeccio | 15,3 | -4,7 | 64 | 0 | 🟢 |
| Maestrale | 14,5 | -5,5 | 67 | 0 | 🟢 |
| Ponente | 14,1 | -5,9 | 51 | 1 | 🟢 |
| Grecale-B | 12,7 | -7,3 | 54 | 2 | 🟢 |
| Scirocco | 9,4 | -10,6 | 54 | 6 | 🟢 |
| Ponente-B | 6,6 | -13,4 | 43 | 2 | 🟢 |
| Tramontana | 0,0 | -20,3 | 45 | 18 | 🛑 |

_Aggiornato: 17/07 16:36_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
