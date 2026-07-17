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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=b3828671)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=2f60be88)

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

- **Scirocco**: dati ridotti avanti di 15,8u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 9,6u — qui gli extra non aiutano
- **Libeccio**: dati ridotti avanti di 2,3u — qui gli extra non aiutano
- **Tramontana**: dati ridotti avanti di 34,1u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 4,9u
- **Zefiro**: dati completi avanti di 2,6u
- **Ponente**: dati ridotti avanti di 2,5u — qui gli extra non aiutano

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 33,8 | +13,8 | 90 | 0 | 🟢 |
| Scirocco-B | 16,5 | -3,5 | 52 | 0 | 🟢 |
| Maestrale-B | 13,7 | -6,3 | 74 | 12 | ⏸ |
| Libeccio-B | 12,9 | -7,1 | 68 | 2 | 🟢 |
| Zefiro | 12,7 | -7,3 | 71 | 0 | 🟢 |
| Grecale | 11,2 | -8,8 | 85 | 3 | 🟢 |
| Libeccio | 10,6 | -9,4 | 73 | 19 | ⏸ |
| Zefiro-B | 10,0 | -10,0 | 51 | 0 | 🟢 |
| Ponente-B | 6,5 | -13,5 | 48 | 2 | 🟢 |
| Grecale-B | 6,3 | -13,7 | 78 | 2 | 🟢 |
| Maestrale | 4,1 | -15,9 | 97 | 0 | 🟢 |
| Ponente | 4,0 | -16,0 | 62 | 5 | ⏸ |
| Scirocco | 0,7 | -19,3 | 79 | 6 | 🟢 |
| Tramontana | 0,0 | -20,3 | 45 | 46 | 🛑 |

_Aggiornato: 17/07 21:01_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
