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

![Coppie: dati completi vs ridotti](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/equity_pairs.png?v=544e5617)

![Delta per coppia](https://raw.githubusercontent.com/Kitem19/ippica-track-record/main/charts/coppie_delta.png?v=c9cede0c)

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

- **Scirocco**: dati ridotti avanti di 16,3u — qui gli extra non aiutano
- **Maestrale**: dati ridotti avanti di 9,3u — qui gli extra non aiutano
- **Libeccio**: dati ridotti avanti di 3,4u — qui gli extra non aiutano
- **Tramontana**: dati ridotti avanti di 36,4u — qui gli extra non aiutano
- **Grecale**: dati completi avanti di 4,6u
- **Zefiro**: dati completi avanti di 2,9u
- **Ponente**: dati ridotti avanti di 2,5u — qui gli extra non aiutano

## Classifica (conteggio ufficiale)

| Sistema | Cassa (u) | P/L (u) | Selezioni | Escluse | Stato |
|---|---|---|---|---|---|
| Tramontana-B | 36,1 | +16,1 | 85 | 0 | 🟢 |
| Scirocco-B | 18,7 | -1,3 | 49 | 0 | 🟢 |
| Zefiro | 16,0 | -4,0 | 66 | 0 | 🟢 |
| Libeccio-B | 14,0 | -6,0 | 63 | 2 | 🟢 |
| Maestrale-B | 13,7 | -6,3 | 74 | 7 | ⏸ |
| Zefiro-B | 13,1 | -6,9 | 46 | 0 | 🟢 |
| Grecale | 11,5 | -8,5 | 80 | 3 | 🟢 |
| Libeccio | 10,6 | -9,4 | 73 | 14 | ⏸ |
| Ponente-B | 7,5 | -12,5 | 47 | 2 | 🟢 |
| Grecale-B | 6,9 | -13,1 | 73 | 2 | 🟢 |
| Ponente | 5,0 | -15,0 | 61 | 1 | 🟢 |
| Maestrale | 4,4 | -15,6 | 92 | 0 | 🟢 |
| Scirocco | 2,4 | -17,6 | 75 | 6 | 🟢 |
| Tramontana | 0,0 | -20,3 | 45 | 41 | 🛑 |

_Aggiornato: 17/07 20:11_
---
*Nessuna delle informazioni qui pubblicate costituisce consiglio di gioco.
Il gioco può causare dipendenza — 18+.*
