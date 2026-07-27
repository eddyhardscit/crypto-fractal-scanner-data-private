# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T00:08:46+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **793**
- Scenari virtuali ancora attivi: **12254**
- Gruppi in attesa dell'uscita originale: **403**
- Gruppi con originale chiuso ma Shadow ancora attive: **390**
- Confronti completati: **45494**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 1669 | 1734 | €-0,77 | 44,8% | 392 | 305 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 1666 | 1731 | +€6,74 | 49,3% | 535 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1666 | 1731 | +€5,12 | 47,0% | 553 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1666 | 1731 | +€3,07 | 45,5% | 562 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1666 | 1731 | +€2,47 | 44,8% | 618 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1665 | 1730 | +€1,86 | 45,4% | 516 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1643 | 1708 | +€0,17 | 40,2% | 194 | 461 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1635 | 1700 | +€8,05 | 45,4% | 430 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1635 | 1700 | +€6,22 | 44,6% | 418 | 58 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1635 | 1700 | +€5,96 | 42,1% | 489 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1624 | 1689 | +€5,11 | 44,4% | 343 | 115 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1620 | 1685 | +€3,92 | 41,7% | 279 | 231 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1588 | 1653 | +€6,73 | 31,9% | 232 | 178 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1588 | 1653 | +€0,38 | 34,4% | 179 | 384 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1543 | 1608 | €-3,96 | 29,0% | 159 | 451 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1531 | 1596 | €-10,92 | 29,4% | 314 | 346 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1525 | 1590 | €-0,79 | 36,7% | 90 | 468 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1525 | 1590 | €-8,37 | 27,0% | 114 | 493 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1519 | 1584 | +€7,06 | 38,8% | 102 | 271 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1411 | 1476 | €-14,96 | 21,8% | 113 | 483 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
