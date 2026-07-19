# Block 3 — Shadow Exit Engine

Generato: 2026-07-19T23:08:34+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **71**
- Scenari virtuali ancora attivi: **1132**
- Gruppi in attesa dell'uscita originale: **67**
- Gruppi con originale chiuso ma Shadow ancora attive: **4**
- Confronti completati: **184**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R150 | 1 | 10 | €-2,54 | 0,0% | 1 | 0 | COLLECTING |
| GB50_R100 | 1 | 9 | €-7,83 | 0,0% | 1 | 1 | COLLECTING |
| GB20_R100 | 1 | 10 | €-8,91 | 0,0% | 3 | 0 | COLLECTING |
| TP_R100 | 1 | 10 | €-9,96 | 0,0% | 3 | 0 | COLLECTING |
| GB30_R100 | 1 | 10 | €-10,89 | 0,0% | 3 | 0 | COLLECTING |
| GB20_R050 | 1 | 11 | €-11,74 | 9,1% | 3 | 0 | COLLECTING |
| GB40_R100 | 1 | 10 | €-12,64 | 0,0% | 2 | 1 | COLLECTING |
| GB30_R050 | 1 | 11 | €-13,10 | 9,1% | 3 | 0 | COLLECTING |
| TP_R050 | 1 | 11 | €-13,60 | 9,1% | 3 | 0 | COLLECTING |
| GB40_R050 | 1 | 11 | €-14,47 | 9,1% | 3 | 0 | COLLECTING |
| GB50_R050 | 1 | 11 | €-15,83 | 9,1% | 3 | 0 | COLLECTING |
| BE_R050 | 1 | 11 | €-22,63 | 0,0% | 4 | 0 | COLLECTING |
| TIME_6H | 0 | 8 | +€21,19 | 87,5% | 0 | 0 | WAITING_FULL_SAMPLE |
| TIME_24H | 0 | 7 | +€18,53 | 71,4% | 0 | 0 | WAITING_FULL_SAMPLE |
| TIME_12H | 0 | 8 | +€17,46 | 75,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| TP_R200 | 0 | 8 | +€0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR15_R100 | 0 | 7 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR20_R100 | 0 | 7 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| ATR30_R100 | 0 | 7 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |
| BE_R100 | 0 | 7 | €0,00 | 0,0% | 0 | 0 | WAITING_FULL_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
