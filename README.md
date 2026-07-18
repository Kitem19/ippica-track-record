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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=0b75f079)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=07bc5b56)

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

- **Scirocco**: dati ridotti avanti di 17,2u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 12,6u — qui gli extra non aiutano
- **Libeccio**: dati ridotti avanti di 3,7u — qui gli extra non aiutano
- **Tramontana**: dati ridotti avanti di 39,9u — qui gli extra non aiutano
- **Grecale**: in sostanziale pareggio — troppo presto per dire
- **Zefiro**: dati ridotti avanti di 4,7u — qui gli extra non aiutano
- **Ponente**: dati ridotti avanti di 3,7u — qui gli extra non aiutano

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 39,6 | +19,6 | 98 | 0 | 🟢 |
| Scirocco-B | 17,1 | -2,9 | 56 | 0 | 🟢 |
| Zefiro-B | 16,2 | -3,8 | 58 | 0 | 🟢 |
| Maestrale-B | 12,1 | -7,9 | 76 | 18 | 🟢 |
| Zefiro | 11,4 | -8,6 | 74 | 3 | 🟢 |
| Libeccio-B | 11,3 | -8,7 | 73 | 2 | 🟢 |
| Grecale | 10,6 | -9,4 | 91 | 3 | 🟢 |
| Grecale-B | 9,0 | -11,0 | 84 | 2 | 🟢 |
| Libeccio | 7,6 | -12,4 | 76 | 25 | 🟢 |
| Ponente-B | 6,7 | -13,3 | 52 | 2 | 🟢 |
| Ponente | 3,0 | -17,0 | 63 | 9 | 🟢 |
| Scirocco | 0,0 | -20,1 | 80 | 14 | 🛑 |
| Tramontana | 0,0 | -20,3 | 45 | 54 | 🛑 |
| Maestrale | 0,0 | -20,5 | 104 | 1 | 🛑 |

_Aggiornato: 18/07 14:51_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
