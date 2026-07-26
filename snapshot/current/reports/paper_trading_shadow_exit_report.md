# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T16:53:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **726**
- Scenari virtuali ancora attivi: **10246**
- Gruppi in attesa dell'uscita originale: **351**
- Gruppi con originale chiuso ma Shadow ancora attive: **375**
- Confronti completati: **44260**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1631 | 1696 | +€7,03 | 49,2% | 521 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1631 | 1696 | +€5,42 | 47,6% | 538 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1631 | 1696 | +€3,36 | 46,2% | 535 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1631 | 1696 | +€2,71 | 45,3% | 592 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1630 | 1695 | +€2,17 | 46,1% | 488 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1618 | 1683 | €-0,53 | 44,9% | 378 | 291 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1602 | 1667 | +€8,10 | 44,8% | 425 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1602 | 1667 | +€6,32 | 44,2% | 411 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1602 | 1667 | +€6,00 | 41,8% | 479 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1602 | 1667 | +€5,17 | 44,2% | 341 | 115 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1598 | 1663 | +€4,02 | 41,5% | 275 | 229 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1581 | 1646 | +€0,88 | 41,3% | 191 | 414 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1568 | 1633 | €-0,10 | 33,8% | 179 | 384 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1548 | 1613 | +€6,24 | 31,1% | 229 | 177 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1537 | 1602 | €-3,95 | 29,2% | 159 | 448 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1521 | 1586 | €-8,37 | 27,0% | 114 | 492 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1510 | 1575 | €-10,70 | 29,8% | 305 | 338 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1482 | 1547 | +€6,91 | 38,3% | 102 | 261 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1433 | 1498 | €-1,69 | 35,3% | 87 | 438 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1399 | 1464 | €-14,80 | 22,0% | 113 | 474 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
