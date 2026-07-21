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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=045df8a1)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=8706cae5)

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

- **Scirocco**: dati ridotti avanti di 14,1u — qui gli extra non aiutano
- **Maestrale**: in sostanziale pareggio — troppo presto per dire
- **Libeccio**: dati completi avanti di 13,4u
- **Tramontana**: dati ridotti avanti di 23,2u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 10,2u
- **Zefiro**: in sostanziale pareggio — troppo presto per dire
- **Ponente**: dati completi avanti di 25,5u

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Ponente | 24,5 | +4,5 | 109 | 17 | ⏸ |
| Tramontana-B | 22,9 | +2,9 | 185 | 0 | 🟢 |
| Zefiro-B | 14,2 | -5,8 | 113 | 0 | 🟢 |
| Zefiro | 14,1 | -5,9 | 145 | 5 | 🟢 |
| Scirocco-B | 14,0 | -6,0 | 122 | 0 | 🟢 |
| Libeccio | 12,5 | -7,5 | 152 | 34 | ⏸ |
| Grecale | 10,0 | -10,0 | 176 | 4 | ⏸ |
| Maestrale-B | 0,0 | -20,0 | 100 | 88 | 🛑 |
| Scirocco | 0,0 | -20,1 | 80 | 99 | 🛑 |
| Grecale-B | 0,0 | -20,2 | 137 | 33 | 🛑 |
| Tramontana | 0,0 | -20,3 | 45 | 147 | 🛑 |
| Maestrale | 0,0 | -20,5 | 104 | 94 | 🛑 |
| Libeccio-B | 0,0 | -20,9 | 119 | 35 | 🛑 |
| Ponente-B | 0,0 | -21,0 | 63 | 27 | 🛑 |

_Aggiornato: 21/07 09:16_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
