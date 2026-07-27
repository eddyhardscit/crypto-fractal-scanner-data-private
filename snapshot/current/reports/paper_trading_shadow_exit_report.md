# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T01:08:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **811**
- Scenari virtuali ancora attivi: **13044**
- Gruppi in attesa dell'uscita originale: **410**
- Gruppi con originale chiuso ma Shadow ancora attive: **401**
- Confronti completati: **47342**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 1706 | 1771 | €-0,51 | 45,6% | 392 | 305 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 1703 | 1768 | +€6,99 | 49,5% | 536 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1703 | 1768 | +€5,37 | 47,3% | 553 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1703 | 1768 | +€3,33 | 45,9% | 562 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1703 | 1768 | +€2,80 | 45,1% | 619 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1702 | 1767 | +€2,10 | 45,3% | 524 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1680 | 1745 | +€0,70 | 40,6% | 195 | 462 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1673 | 1738 | +€8,11 | 45,7% | 430 | 33 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1673 | 1738 | +€6,28 | 45,0% | 418 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1673 | 1738 | +€6,11 | 42,5% | 489 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1670 | 1735 | +€5,21 | 45,0% | 343 | 117 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1666 | 1731 | +€3,97 | 42,1% | 279 | 237 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1639 | 1704 | +€0,26 | 34,3% | 190 | 394 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1615 | 1680 | +€6,52 | 31,9% | 232 | 183 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1603 | 1668 | €-3,60 | 29,4% | 160 | 472 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1569 | 1634 | €-1,31 | 36,4% | 90 | 487 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1567 | 1632 | €-10,59 | 29,2% | 325 | 349 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1564 | 1629 | €-8,37 | 26,8% | 115 | 509 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1545 | 1610 | +€6,82 | 38,6% | 102 | 276 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1450 | 1515 | €-14,80 | 21,8% | 114 | 499 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
