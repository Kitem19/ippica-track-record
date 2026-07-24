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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=74f3e80a)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=6126445e)

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

- **Scirocco**: dati ridotti avanti di 17,8u — qui gli extra non aiutano
- **Maestrale**: in sostanziale pareggio — troppo presto per dire
- **Libeccio**: in sostanziale pareggio — troppo presto per dire
- **Tramontana**: dati ridotti avanti di 11,7u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 17,1u
- **Zefiro**: dati completi avanti di 16,8u
- **Ponente**: dati completi avanti di 8,5u

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Scirocco-B | 17,7 | -2,3 | 203 | 0 | 🟢 |
| Grecale | 16,8 | -3,2 | 273 | 4 | 🟢 |
| Zefiro | 16,3 | -3,7 | 240 | 5 | 🟢 |
| Tramontana-B | 11,4 | -8,6 | 302 | 0 | 🟢 |
| Ponente | 7,5 | -12,5 | 186 | 28 | 🟢 |
| Maestrale-B | 0,0 | -20,0 | 100 | 201 | 🛑 |
| Scirocco | 0,0 | -20,1 | 80 | 212 | 🛑 |
| Grecale-B | 0,0 | -20,2 | 137 | 143 | 🛑 |
| Tramontana | 0,0 | -20,3 | 45 | 273 | 🛑 |
| Zefiro-B | 0,0 | -20,5 | 143 | 50 | 🛑 |
| Maestrale | 0,0 | -20,5 | 104 | 223 | 🛑 |
| Libeccio | 0,0 | -20,6 | 181 | 132 | 🛑 |
| Libeccio-B | 0,0 | -20,9 | 119 | 145 | 🛑 |
| Ponente-B | 0,0 | -21,0 | 63 | 70 | 🛑 |

_Aggiornato: 25/07 01:26_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
