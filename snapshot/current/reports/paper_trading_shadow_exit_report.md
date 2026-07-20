# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T04:08:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **85**
- Scenari virtuali ancora attivi: **1151**
- Gruppi in attesa dell'uscita originale: **70**
- Gruppi con originale chiuso ma Shadow ancora attive: **15**
- Confronti completati: **628**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 14 | 36 | +€12,23 | 47,2% | 9 | 0 | PRELIMINARY_SAMPLE |
| GB30_R050 | 14 | 36 | +€9,21 | 47,2% | 9 | 0 | PRELIMINARY_SAMPLE |
| GB40_R050 | 14 | 36 | +€6,88 | 47,2% | 9 | 0 | PRELIMINARY_SAMPLE |
| TP_R050 | 14 | 36 | +€5,42 | 47,2% | 9 | 0 | PRELIMINARY_SAMPLE |
| GB50_R050 | 14 | 36 | +€4,09 | 47,2% | 9 | 0 | PRELIMINARY_SAMPLE |
| TP_R150 | 13 | 32 | +€9,10 | 40,6% | 5 | 1 | PRELIMINARY_SAMPLE |
| GB20_R100 | 13 | 34 | +€6,42 | 44,1% | 8 | 1 | PRELIMINARY_SAMPLE |
| GB30_R100 | 13 | 34 | +€3,16 | 44,1% | 8 | 1 | PRELIMINARY_SAMPLE |
| TP_R100 | 13 | 34 | +€0,76 | 44,1% | 8 | 1 | PRELIMINARY_SAMPLE |
| GB40_R100 | 13 | 34 | €-0,10 | 44,1% | 7 | 2 | PRELIMINARY_SAMPLE |
| GB50_R100 | 13 | 34 | €-3,01 | 41,2% | 7 | 3 | PRELIMINARY_SAMPLE |
| TIME_6H | 13 | 35 | €-6,52 | 51,4% | 11 | 3 | PRELIMINARY_SAMPLE |
| TP_R200 | 12 | 30 | +€17,21 | 46,7% | 2 | 1 | PRELIMINARY_SAMPLE |
| BE_R050 | 12 | 30 | €-1,97 | 33,3% | 8 | 0 | PRELIMINARY_SAMPLE |
| ATR15_R100 | 10 | 28 | €-3,67 | 50,0% | 2 | 2 | PRELIMINARY_SAMPLE |
| TIME_12H | 9 | 28 | +€8,32 | 60,7% | 6 | 1 | COLLECTING |
| TIME_24H | 9 | 24 | +€3,61 | 66,7% | 2 | 2 | COLLECTING |
| ATR20_R100 | 9 | 24 | +€2,38 | 50,0% | 0 | 1 | COLLECTING |
| BE_R100 | 9 | 23 | +€1,92 | 43,5% | 0 | 1 | COLLECTING |
| ATR30_R100 | 9 | 24 | +€1,55 | 41,7% | 1 | 1 | COLLECTING |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
