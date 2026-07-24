# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T02:53:43+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **332**
- Scenari virtuali ancora attivi: **2842**
- Gruppi in attesa dell'uscita originale: **163**
- Gruppi con originale chiuso ma Shadow ancora attive: **169**
- Confronti completati: **14805**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 703 | 766 | +€5,73 | 48,4% | 200 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 703 | 766 | +€3,65 | 47,1% | 205 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 703 | 766 | +€1,42 | 45,7% | 211 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 703 | 766 | +€0,40 | 45,8% | 223 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 702 | 765 | €-0,48 | 50,3% | 162 | 103 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 698 | 761 | +€0,27 | 44,3% | 202 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 696 | 759 | +€4,67 | 41,8% | 169 | 21 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 696 | 759 | +€2,77 | 41,6% | 158 | 33 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 696 | 759 | +€2,48 | 39,8% | 184 | 21 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 696 | 759 | +€1,65 | 41,2% | 135 | 57 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 691 | 754 | +€1,48 | 37,9% | 97 | 114 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 690 | 753 | €-1,36 | 32,8% | 58 | 170 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 676 | 739 | +€1,06 | 44,5% | 80 | 157 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 675 | 738 | +€1,66 | 30,8% | 78 | 83 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 666 | 729 | €-4,31 | 29,4% | 43 | 193 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 643 | 706 | +€0,49 | 36,0% | 36 | 124 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 643 | 706 | €-9,34 | 25,1% | 39 | 197 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 639 | 702 | €-10,75 | 27,6% | 123 | 127 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 631 | 694 | €-5,46 | 32,6% | 44 | 193 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 595 | 658 | €-16,83 | 19,5% | 38 | 195 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
