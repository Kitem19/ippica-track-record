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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=d5645560)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=63d0ec94)

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

- **Scirocco**: dati ridotti avanti di 15,3u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 4,0u — qui gli extra non aiutano
- **Libeccio**: dati completi avanti di 2,3u
- **Tramontana**: dati ridotti avanti di 28,3u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 5,6u
- **Zefiro**: dati ridotti avanti di 10,6u — qui gli extra non aiutano
- **Ponente**: dati completi avanti di 6,1u

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 28,0 | +8,0 | 114 | 0 | 🟢 |
| Zefiro-B | 25,9 | +5,9 | 67 | 0 | 🟢 |
| Zefiro | 15,4 | -4,6 | 90 | 3 | 🟢 |
| Scirocco-B | 15,2 | -4,8 | 68 | 0 | 🟢 |
| Libeccio | 10,7 | -9,3 | 93 | 25 | 🟢 |
| Grecale | 9,9 | -10,1 | 109 | 3 | 🟢 |
| Libeccio-B | 8,5 | -11,5 | 88 | 2 | 🟢 |
| Ponente | 7,1 | -12,9 | 70 | 9 | 🟢 |
| Grecale-B | 4,4 | -15,6 | 99 | 2 | 🟢 |
| Maestrale-B | 3,5 | -16,5 | 87 | 24 | ⏸ |
| Ponente-B | 1,0 | -19,0 | 61 | 2 | 🟢 |
| Scirocco | 0,0 | -20,1 | 80 | 32 | 🛑 |
| Tramontana | 0,0 | -20,3 | 45 | 70 | 🛑 |
| Maestrale | 0,0 | -20,5 | 104 | 18 | 🛑 |

_Aggiornato: 18/07 16:56_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
