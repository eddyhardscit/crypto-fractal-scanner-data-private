# Block 3 — Shadow Exit Engine

Generato: 2026-07-23T20:38:43+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **323**
- Scenari virtuali ancora attivi: **3058**
- Gruppi in attesa dell'uscita originale: **188**
- Gruppi con originale chiuso ma Shadow ancora attive: **135**
- Confronti completati: **13123**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 617 | 680 | +€6,37 | 46,6% | 168 | 1 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 617 | 680 | +€0,81 | 43,8% | 190 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 616 | 679 | +€4,32 | 45,5% | 170 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 616 | 679 | +€2,15 | 44,5% | 172 | 13 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 613 | 676 | +€0,79 | 43,0% | 168 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 610 | 673 | +€0,96 | 51,0% | 127 | 88 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 608 | 671 | +€4,00 | 38,2% | 144 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 608 | 671 | +€2,14 | 37,6% | 136 | 31 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 608 | 671 | +€1,30 | 37,7% | 112 | 52 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 608 | 671 | +€1,27 | 35,6% | 161 | 19 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 605 | 668 | +€1,34 | 34,7% | 80 | 99 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 600 | 663 | €-0,21 | 32,1% | 36 | 144 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 596 | 659 | +€0,86 | 27,3% | 72 | 72 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 594 | 657 | €-3,01 | 28,6% | 42 | 156 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 583 | 646 | +€4,04 | 45,2% | 56 | 125 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 583 | 646 | +€0,39 | 33,0% | 33 | 110 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 569 | 632 | €-8,12 | 24,2% | 38 | 156 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 566 | 629 | €-2,74 | 31,5% | 33 | 167 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 538 | 601 | €-7,13 | 28,3% | 95 | 86 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 508 | 571 | €-14,49 | 18,4% | 37 | 140 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
