# Block 3 — Shadow Exit Engine

Generato: 2026-07-26T14:53:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **699**
- Scenari virtuali ancora attivi: **9372**
- Gruppi in attesa dell'uscita originale: **321**
- Gruppi con originale chiuso ma Shadow ancora attive: **378**
- Confronti completati: **43885**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1621 | 1686 | +€7,08 | 49,5% | 519 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1621 | 1686 | +€5,46 | 47,9% | 536 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1621 | 1686 | +€3,38 | 46,4% | 533 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1621 | 1686 | +€2,73 | 45,6% | 590 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1620 | 1685 | +€2,19 | 46,4% | 486 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1599 | 1664 | €-0,60 | 45,0% | 376 | 286 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1592 | 1657 | +€8,15 | 45,1% | 423 | 32 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1592 | 1657 | +€6,36 | 44,5% | 409 | 57 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1592 | 1657 | +€6,04 | 42,0% | 477 | 30 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1591 | 1656 | +€5,22 | 44,5% | 339 | 114 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1587 | 1652 | +€4,06 | 41,8% | 273 | 228 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1560 | 1625 | €-0,10 | 34,0% | 179 | 384 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1545 | 1610 | +€0,88 | 41,1% | 191 | 401 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1535 | 1600 | +€6,42 | 31,4% | 229 | 174 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1528 | 1593 | €-3,96 | 29,3% | 159 | 447 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1513 | 1578 | €-8,41 | 27,2% | 114 | 492 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1500 | 1565 | €-10,65 | 30,0% | 305 | 336 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1469 | 1534 | +€7,08 | 38,5% | 102 | 258 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1421 | 1486 | €-1,71 | 35,3% | 87 | 435 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1389 | 1454 | €-14,76 | 22,1% | 113 | 472 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
