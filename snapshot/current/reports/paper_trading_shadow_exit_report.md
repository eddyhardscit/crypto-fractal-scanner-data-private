# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T02:08:36+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **77**
- Scenari virtuali ancora attivi: **1041**
- Gruppi in attesa dell'uscita originale: **64**
- Gruppi con originale chiuso ma Shadow ancora attive: **13**
- Confronti completati: **415**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R150 | 4 | 21 | +€17,85 | 33,3% | 2 | 1 | COLLECTING |
| GB20_R100 | 4 | 23 | +€16,19 | 39,1% | 4 | 1 | COLLECTING |
| GB30_R100 | 4 | 23 | +€12,63 | 39,1% | 4 | 1 | COLLECTING |
| TP_R100 | 4 | 23 | +€9,14 | 39,1% | 4 | 1 | COLLECTING |
| GB40_R100 | 4 | 23 | +€8,68 | 39,1% | 3 | 2 | COLLECTING |
| GB20_R050 | 4 | 24 | +€8,14 | 41,7% | 5 | 0 | COLLECTING |
| GB50_R100 | 4 | 23 | +€5,70 | 34,8% | 3 | 3 | COLLECTING |
| GB30_R050 | 4 | 24 | +€5,33 | 41,7% | 5 | 0 | COLLECTING |
| GB40_R050 | 4 | 24 | +€3,07 | 41,7% | 5 | 0 | COLLECTING |
| TIME_6H | 4 | 24 | +€1,32 | 50,0% | 7 | 3 | COLLECTING |
| GB50_R050 | 4 | 24 | +€0,69 | 41,7% | 5 | 0 | COLLECTING |
| TP_R050 | 4 | 24 | +€0,26 | 41,7% | 5 | 0 | COLLECTING |
| BE_R050 | 4 | 21 | €-12,84 | 19,0% | 6 | 0 | COLLECTING |
| TP_R200 | 3 | 16 | +€21,11 | 25,0% | 0 | 1 | COLLECTING |
| ATR15_R100 | 3 | 20 | €-1,21 | 40,0% | 1 | 2 | COLLECTING |
| TIME_12H | 2 | 16 | +€18,59 | 62,5% | 3 | 0 | COLLECTING |
| TIME_24H | 2 | 12 | +€12,75 | 66,7% | 0 | 1 | COLLECTING |
| ATR20_R100 | 2 | 17 | +€2,64 | 35,3% | 0 | 1 | COLLECTING |
| BE_R100 | 2 | 16 | +€2,01 | 25,0% | 0 | 1 | COLLECTING |
| ATR30_R100 | 2 | 17 | +€1,48 | 23,5% | 1 | 1 | COLLECTING |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
