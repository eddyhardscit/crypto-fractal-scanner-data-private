# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T06:53:43+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **350**
- Scenari virtuali ancora attivi: **2991**
- Gruppi in attesa dell'uscita originale: **166**
- Gruppi con originale chiuso ma Shadow ancora attive: **184**
- Confronti completati: **15458**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 742 | 805 | +€7,27 | 50,7% | 200 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 742 | 805 | +€5,10 | 49,4% | 205 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 742 | 805 | +€2,79 | 48,1% | 211 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 742 | 805 | +€1,64 | 48,2% | 223 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 739 | 802 | +€1,42 | 46,4% | 206 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 728 | 791 | €-0,82 | 50,4% | 166 | 109 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 726 | 789 | +€5,94 | 43,6% | 169 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 726 | 789 | +€3,95 | 43,5% | 158 | 34 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 726 | 789 | +€3,80 | 41,7% | 184 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 726 | 789 | +€2,72 | 43,1% | 135 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 723 | 786 | +€2,31 | 39,8% | 99 | 115 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 722 | 785 | €-1,23 | 34,8% | 61 | 171 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 720 | 783 | €-0,10 | 43,7% | 85 | 181 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 701 | 764 | €-4,42 | 30,9% | 44 | 201 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 689 | 752 | +€1,40 | 31,1% | 78 | 88 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 680 | 743 | €-9,35 | 26,8% | 40 | 207 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 678 | 741 | €-9,93 | 29,4% | 125 | 130 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 661 | 724 | €-0,04 | 36,3% | 36 | 131 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 652 | 715 | €-5,86 | 33,0% | 46 | 200 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 633 | 696 | €-16,53 | 21,6% | 39 | 206 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
