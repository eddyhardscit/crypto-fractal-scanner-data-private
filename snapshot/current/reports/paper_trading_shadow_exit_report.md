# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T22:08:43+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **394**
- Scenari virtuali ancora attivi: **3691**
- Gruppi in attesa dell'uscita originale: **204**
- Gruppi con originale chiuso ma Shadow ancora attive: **190**
- Confronti completati: **18121**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 874 | 937 | €-1,08 | 49,5% | 224 | 119 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 873 | 936 | +€6,11 | 51,1% | 247 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 873 | 936 | +€3,98 | 50,0% | 252 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 873 | 936 | +€1,69 | 48,7% | 259 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 873 | 936 | +€0,99 | 49,0% | 269 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 867 | 930 | +€0,48 | 47,4% | 251 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 859 | 922 | +€5,40 | 45,2% | 209 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 859 | 922 | +€3,58 | 45,2% | 197 | 35 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 859 | 922 | +€3,56 | 43,7% | 223 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 858 | 921 | €-1,68 | 43,3% | 125 | 201 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 856 | 919 | +€2,26 | 44,9% | 172 | 59 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 848 | 911 | +€1,50 | 42,2% | 133 | 116 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 847 | 910 | €-3,17 | 35,7% | 86 | 193 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 830 | 893 | +€3,61 | 34,6% | 104 | 92 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 829 | 892 | €-6,99 | 30,2% | 70 | 238 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 828 | 891 | €-4,43 | 36,3% | 76 | 233 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 809 | 872 | €-11,45 | 29,0% | 170 | 146 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 801 | 864 | €-11,32 | 27,2% | 65 | 235 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 796 | 859 | +€0,75 | 38,4% | 63 | 146 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 749 | 812 | €-17,83 | 22,4% | 64 | 233 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
