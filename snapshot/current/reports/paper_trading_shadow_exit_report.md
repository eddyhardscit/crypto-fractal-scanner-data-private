# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T00:08:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **392**
- Scenari virtuali ancora attivi: **3513**
- Gruppi in attesa dell'uscita originale: **204**
- Gruppi con originale chiuso ma Shadow ancora attive: **188**
- Confronti completati: **18506**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 895 | 958 | +€5,15 | 50,6% | 262 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 895 | 958 | +€2,97 | 49,6% | 267 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 895 | 958 | +€0,66 | 48,2% | 274 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 895 | 958 | €-0,02 | 48,5% | 285 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 893 | 956 | €-2,06 | 48,8% | 238 | 121 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 889 | 952 | €-0,62 | 47,1% | 266 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 879 | 942 | +€4,62 | 44,8% | 223 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 879 | 942 | +€2,89 | 43,3% | 237 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 879 | 942 | +€2,76 | 44,8% | 211 | 35 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 876 | 939 | +€1,46 | 44,4% | 186 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 875 | 938 | €-2,31 | 42,8% | 138 | 202 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 867 | 930 | +€0,66 | 41,7% | 147 | 116 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 854 | 917 | €-3,47 | 35,7% | 90 | 193 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 848 | 911 | +€3,34 | 34,2% | 117 | 92 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 847 | 910 | €-7,39 | 30,3% | 75 | 243 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 837 | 900 | €-4,76 | 36,1% | 80 | 235 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 830 | 893 | +€2,43 | 39,4% | 69 | 146 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 826 | 889 | €-12,71 | 28,6% | 184 | 147 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 819 | 882 | €-11,67 | 26,6% | 70 | 240 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 767 | 830 | €-18,06 | 21,9% | 69 | 238 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
