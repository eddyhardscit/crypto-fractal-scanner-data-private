# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T19:08:45+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **399**
- Scenari virtuali ancora attivi: **3480**
- Gruppi in attesa dell'uscita originale: **200**
- Gruppi con originale chiuso ma Shadow ancora attive: **199**
- Confronti completati: **17426**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 840 | 903 | +€5,56 | 49,6% | 244 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 840 | 903 | +€3,41 | 48,5% | 249 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 840 | 903 | +€1,10 | 47,2% | 256 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 840 | 903 | +€0,27 | 47,4% | 267 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 835 | 898 | €-0,22 | 45,8% | 249 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 834 | 897 | +€4,81 | 43,9% | 207 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 834 | 897 | +€2,87 | 43,9% | 195 | 35 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 834 | 897 | +€2,87 | 42,4% | 221 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 832 | 895 | +€1,51 | 43,6% | 171 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 826 | 889 | €-1,33 | 48,6% | 214 | 113 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 824 | 887 | +€0,80 | 40,7% | 132 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 815 | 878 | €-0,49 | 43,7% | 115 | 191 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 807 | 870 | €-2,96 | 34,8% | 83 | 178 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 801 | 864 | +€2,68 | 32,9% | 101 | 91 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 789 | 852 | €-6,60 | 29,0% | 67 | 223 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 778 | 841 | €-3,04 | 36,4% | 66 | 218 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 770 | 833 | €-11,67 | 27,9% | 167 | 139 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 761 | 824 | €-10,98 | 25,8% | 62 | 220 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 757 | 820 | +€1,60 | 37,9% | 54 | 136 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 709 | 772 | €-17,81 | 20,7% | 61 | 218 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
