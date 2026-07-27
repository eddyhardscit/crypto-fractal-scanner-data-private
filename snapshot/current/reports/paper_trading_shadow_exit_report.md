# Block 3 — Shadow Exit Engine

Generato: 2026-07-27T06:08:49+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **856**
- Scenari virtuali ancora attivi: **14256**
- Gruppi in attesa dell'uscita originale: **447**
- Gruppi con originale chiuso ma Shadow ancora attive: **409**
- Confronti completati: **50228**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 1765 | 1830 | +€6,80 | 48,8% | 542 | 2 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 1765 | 1830 | +€5,21 | 46,7% | 559 | 16 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 1765 | 1830 | +€3,20 | 45,3% | 568 | 38 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 1765 | 1830 | +€2,73 | 44,5% | 625 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 1764 | 1829 | +€1,99 | 44,7% | 530 | 87 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 1762 | 1827 | €-0,40 | 45,0% | 392 | 308 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 1753 | 1818 | +€1,28 | 40,7% | 195 | 463 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 1732 | 1797 | +€6,01 | 41,8% | 495 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 1726 | 1791 | +€8,06 | 45,1% | 430 | 33 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 1726 | 1791 | +€6,26 | 44,4% | 418 | 59 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 1725 | 1790 | +€5,17 | 44,3% | 343 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 1719 | 1784 | +€3,97 | 41,6% | 279 | 237 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 1694 | 1759 | +€0,29 | 33,5% | 192 | 397 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 1669 | 1734 | +€6,45 | 31,4% | 232 | 183 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 1669 | 1734 | €-1,82 | 35,6% | 90 | 524 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 1656 | 1721 | €-3,48 | 28,7% | 164 | 472 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 1629 | 1694 | €-7,74 | 26,7% | 118 | 510 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 1620 | 1685 | €-10,20 | 28,4% | 330 | 349 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 1606 | 1671 | +€6,32 | 37,6% | 102 | 289 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 1500 | 1565 | €-14,39 | 21,1% | 117 | 500 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
