# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T11:23:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **103**
- Scenari virtuali ancora attivi: **1231**
- Gruppi in attesa dell'uscita originale: **65**
- Gruppi con originale chiuso ma Shadow ancora attive: **38**
- Confronti completati: **1481**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 50 | 82 | +€6,88 | 47,6% | 21 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 50 | 81 | +€6,57 | 44,4% | 19 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 50 | 82 | +€4,04 | 46,3% | 22 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 50 | 81 | +€2,99 | 43,2% | 20 | 2 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 50 | 81 | +€2,00 | 44,4% | 19 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 50 | 82 | +€1,28 | 43,9% | 24 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 50 | 82 | €-0,27 | 47,6% | 21 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 50 | 81 | €-0,85 | 42,0% | 19 | 3 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 49 | 73 | +€2,34 | 31,5% | 14 | 6 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 48 | 71 | +€9,48 | 35,2% | 9 | 7 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 45 | 77 | +€3,20 | 45,5% | 20 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 43 | 78 | €-6,39 | 35,9% | 22 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 42 | 73 | +€1,99 | 43,8% | 12 | 5 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 42 | 74 | €-8,27 | 24,3% | 19 | 10 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 40 | 71 | €-6,59 | 35,2% | 7 | 12 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 35 | 63 | €-6,69 | 33,3% | 2 | 12 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 34 | 69 | €-2,89 | 36,2% | 15 | 8 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 34 | 62 | €-8,77 | 25,8% | 3 | 14 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 34 | 61 | €-8,91 | 26,2% | 2 | 14 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 29 | 57 | €-7,25 | 33,3% | 9 | 8 | PRELIMINARY_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
