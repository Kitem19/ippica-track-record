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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=34914300)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=3adac0c2)

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

- **Scirocco**: dati ridotti avanti di 19,7u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 16,0u — qui gli extra non aiutano
- **Libeccio**: dati completi avanti di 11,2u
- **Tramontana**: dati ridotti avanti di 39,0u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 8,0u
- **Zefiro**: dati completi avanti di 4,8u
- **Ponente**: dati completi avanti di 8,1u

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 38,7 | +18,7 | 53 | 0 | 🟢 |
| Scirocco-B | 24,7 | +4,7 | 31 | 0 | 🟢 |
| Maestrale-B | 24,1 | +4,1 | 57 | 0 | 🟢 |
| Zefiro | 23,5 | +3,5 | 46 | 0 | 🟢 |
| Libeccio | 21,3 | +1,3 | 58 | 0 | 🟢 |
| Zefiro-B | 18,7 | -1,3 | 33 | 0 | 🟢 |
| Ponente | 16,1 | -3,9 | 49 | 1 | 🟢 |
| Grecale | 15,0 | -5,0 | 54 | 3 | 🟢 |
| Libeccio-B | 10,1 | -9,9 | 42 | 2 | 🟢 |
| Maestrale | 8,1 | -11,9 | 61 | 0 | 🟢 |
| Ponente-B | 8,0 | -12,0 | 40 | 2 | 🟢 |
| Grecale-B | 7,0 | -13,0 | 49 | 2 | 🟢 |
| Scirocco | 5,0 | -15,0 | 49 | 6 | 🟢 |
| Tramontana | 0,0 | -20,3 | 45 | 13 | 🛑 |

_Aggiornato: 17/07 15:36_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
