# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T06:08:53+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **423**
- Scenari virtuali ancora attivi: **3773**
- Gruppi in attesa dell'uscita originale: **200**
- Gruppi con originale chiuso ma Shadow ancora attive: **223**
- Confronti completati: **19522**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 961 | 1025 | €-2,77 | 48,7% | 264 | 125 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 960 | 1024 | +€4,40 | 50,4% | 290 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 960 | 1024 | +€2,19 | 49,1% | 298 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 960 | 1024 | €-0,06 | 47,8% | 306 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 960 | 1024 | €-0,17 | 48,4% | 313 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 953 | 1017 | €-1,31 | 46,7% | 297 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 942 | 1006 | +€3,08 | 43,4% | 265 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 929 | 993 | €-1,73 | 43,9% | 139 | 212 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 924 | 988 | +€4,91 | 45,2% | 237 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 922 | 986 | +€3,03 | 45,3% | 223 | 35 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 921 | 985 | +€1,56 | 44,9% | 198 | 61 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 911 | 975 | +€0,71 | 42,5% | 159 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 899 | 963 | +€3,83 | 34,2% | 118 | 92 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 892 | 956 | €-3,80 | 36,6% | 81 | 257 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 888 | 952 | €-3,17 | 35,7% | 91 | 199 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 876 | 940 | €-13,04 | 28,6% | 201 | 149 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 875 | 939 | €-6,90 | 30,7% | 76 | 244 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 860 | 924 | +€3,28 | 40,6% | 70 | 146 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 854 | 918 | €-10,57 | 27,6% | 70 | 243 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 794 | 858 | €-17,04 | 22,6% | 69 | 239 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
