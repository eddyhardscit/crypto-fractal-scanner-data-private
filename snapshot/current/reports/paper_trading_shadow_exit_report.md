# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T20:08:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **366**
- Scenari virtuali ancora attivi: **3103**
- Gruppi in attesa dell'uscita originale: **181**
- Gruppi con originale chiuso ma Shadow ancora attive: **185**
- Confronti completati: **18019**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 864 | 927 | +€6,01 | 50,7% | 246 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 864 | 927 | +€3,89 | 49,6% | 251 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 864 | 927 | +€1,62 | 48,3% | 258 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 864 | 927 | +€0,86 | 48,7% | 268 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 859 | 922 | +€0,33 | 47,0% | 251 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 858 | 921 | +€5,45 | 45,3% | 208 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 858 | 921 | +€3,64 | 45,3% | 196 | 35 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 858 | 921 | +€3,62 | 43,8% | 222 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 856 | 919 | +€2,26 | 44,9% | 172 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 855 | 918 | €-0,67 | 49,9% | 215 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 849 | 912 | €-1,58 | 43,8% | 124 | 201 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 848 | 911 | +€1,50 | 42,2% | 133 | 116 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 847 | 910 | €-3,17 | 35,7% | 86 | 193 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 829 | 892 | €-6,99 | 30,2% | 70 | 238 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 826 | 889 | +€3,47 | 34,4% | 103 | 92 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 818 | 881 | €-4,43 | 36,7% | 75 | 232 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 801 | 864 | €-11,32 | 27,2% | 65 | 235 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 801 | 864 | €-11,56 | 29,3% | 170 | 146 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 791 | 854 | +€0,35 | 38,2% | 63 | 146 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 749 | 812 | €-17,83 | 22,4% | 64 | 233 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
