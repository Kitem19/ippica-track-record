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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=27dc3909)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=edf260c7)

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

- **Scirocco**: dati ridotti avanti di 21,9u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 9,8u — qui gli extra non aiutano
- **Libeccio**: dati ridotti avanti di 5,8u — qui gli extra non aiutano
- **Tramontana**: dati ridotti avanti di 34,9u — qui gli extra non aiutano
- **Grecale**: dati ridotti avanti di 4,2u — qui gli extra non aiutano
- **Zefiro**: dati ridotti avanti di 9,3u — qui gli extra non aiutano
- **Ponente**: dati ridotti avanti di 3,7u — qui gli extra non aiutano

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 34,6 | +14,6 | 103 | 0 | 🟢 |
| Scirocco-B | 21,9 | +1,9 | 61 | 0 | 🟢 |
| Zefiro-B | 17,6 | -2,4 | 64 | 0 | 🟢 |
| Grecale-B | 13,6 | -6,4 | 89 | 2 | 🟢 |
| Libeccio-B | 9,6 | -10,4 | 79 | 2 | 🟢 |
| Grecale | 9,4 | -10,6 | 98 | 3 | 🟢 |
| Maestrale-B | 9,3 | -10,7 | 82 | 18 | 🟢 |
| Zefiro | 8,4 | -11,6 | 80 | 3 | 🟢 |
| Ponente-B | 6,7 | -13,3 | 54 | 2 | 🟢 |
| Libeccio | 3,8 | -16,2 | 82 | 25 | 🟢 |
| Ponente | 3,0 | -17,0 | 65 | 9 | 🟢 |
| Scirocco | 0,0 | -20,1 | 80 | 21 | 🛑 |
| Tramontana | 0,0 | -20,3 | 45 | 60 | 🛑 |
| Maestrale | 0,0 | -20,5 | 104 | 8 | 🛑 |

_Aggiornato: 18/07 15:41_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
