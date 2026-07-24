# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T01:53:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **349**
- Scenari virtuali ancora attivi: **3092**
- Gruppi in attesa dell'uscita originale: **177**
- Gruppi con originale chiuso ma Shadow ancora attive: **172**
- Confronti completati: **13915**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 665 | 728 | +€5,10 | 46,6% | 194 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 665 | 728 | +€3,00 | 45,5% | 197 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 665 | 728 | +€0,73 | 44,0% | 203 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 665 | 728 | €-0,44 | 43,5% | 219 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 665 | 728 | €-0,60 | 49,5% | 153 | 100 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 662 | 725 | €-0,51 | 42,3% | 196 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 658 | 721 | +€3,89 | 39,4% | 165 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 658 | 721 | +€1,99 | 39,3% | 154 | 32 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 658 | 721 | +€1,56 | 37,0% | 182 | 20 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 658 | 721 | +€0,87 | 38,6% | 133 | 56 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 644 | 707 | +€0,95 | 35,5% | 95 | 104 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 637 | 700 | +€1,75 | 28,6% | 77 | 74 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 635 | 698 | €-0,78 | 30,9% | 49 | 155 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 626 | 689 | +€2,97 | 44,3% | 80 | 131 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 613 | 676 | +€0,92 | 34,5% | 36 | 115 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 610 | 673 | €-3,05 | 28,2% | 42 | 162 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 586 | 649 | €-8,11 | 23,9% | 38 | 163 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 582 | 645 | €-3,39 | 31,3% | 44 | 168 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 578 | 641 | €-8,97 | 26,8% | 118 | 93 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 525 | 588 | €-14,33 | 18,2% | 37 | 147 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
