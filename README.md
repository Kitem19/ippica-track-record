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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=3bf815d8)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=567c5a14)

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

- **Scirocco**: dati ridotti avanti di 12,6u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 4,0u — qui gli extra non aiutano
- **Libeccio**: dati completi avanti di 12,9u
- **Tramontana**: dati ridotti avanti di 32,8u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 10,0u
- **Zefiro**: dati ridotti avanti di 6,5u — qui gli extra non aiutano
- **Ponente**: dati completi avanti di 16,1u

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 32,5 | +12,5 | 122 | 0 | 🟢 |
| Zefiro-B | 25,1 | +5,1 | 75 | 0 | 🟢 |
| Libeccio | 20,7 | +0,7 | 102 | 25 | 🟢 |
| Zefiro | 18,6 | -1,4 | 97 | 3 | 🟢 |
| Grecale | 17,2 | -2,8 | 118 | 3 | 🟢 |
| Ponente | 15,1 | -4,9 | 77 | 9 | 🟢 |
| Scirocco-B | 12,5 | -7,5 | 74 | 0 | 🟢 |
| Libeccio-B | 7,8 | -12,2 | 94 | 2 | 🟢 |
| Grecale-B | 7,2 | -12,8 | 107 | 2 | 🟢 |
| Maestrale-B | 3,5 | -16,5 | 87 | 34 | ⏸ |
| Scirocco | 0,0 | -20,1 | 80 | 41 | 🛑 |
| Tramontana | 0,0 | -20,3 | 45 | 79 | 🛑 |
| Maestrale | 0,0 | -20,5 | 104 | 27 | 🛑 |
| Ponente-B | 0,0 | -21,0 | 63 | 2 | 🛑 |

_Aggiornato: 18/07 18:11_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
