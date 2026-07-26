# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T19:53:46+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **752**
- Scenari virtuali ancora attivi: **11073**
- Gruppi in attesa dell'uscita originale: **369**
- Gruppi con originale chiuso ma Shadow ancora attive: **383**
- Confronti completati: **44962**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1654 | 1719 | +€6,96 | 49,6% | 525 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1654 | 1719 | +€5,34 | 47,2% | 543 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1654 | 1719 | +€3,28 | 45,8% | 552 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1654 | 1719 | +€2,66 | 45,0% | 608 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1653 | 1718 | +€2,08 | 45,6% | 506 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1637 | 1702 | €-0,82 | 44,5% | 381 | 305 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1621 | 1686 | +€8,15 | 45,3% | 425 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1621 | 1686 | +€6,35 | 44,6% | 413 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1621 | 1686 | +€6,08 | 42,3% | 479 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1621 | 1686 | +€5,18 | 44,5% | 341 | 115 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1615 | 1680 | +€4,01 | 41,8% | 277 | 229 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1612 | 1677 | +€0,43 | 40,8% | 191 | 438 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1571 | 1636 | €-0,09 | 33,8% | 179 | 384 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1562 | 1627 | +€6,55 | 31,5% | 229 | 178 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1541 | 1606 | €-3,94 | 29,1% | 159 | 450 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1523 | 1588 | €-8,36 | 27,0% | 114 | 492 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1518 | 1583 | €-10,73 | 29,6% | 308 | 341 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1494 | 1559 | +€6,83 | 38,1% | 102 | 269 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1474 | 1539 | €-0,59 | 36,3% | 87 | 448 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1404 | 1469 | €-14,77 | 21,9% | 113 | 477 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
