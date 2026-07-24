# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T21:08:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **386**
- Scenari virtuali ancora attivi: **3491**
- Gruppi in attesa dell'uscita originale: **193**
- Gruppi con originale chiuso ma Shadow ancora attive: **193**
- Confronti completati: **18092**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 872 | 935 | +€6,20 | 51,1% | 246 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 872 | 935 | +€4,06 | 50,1% | 251 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 872 | 935 | +€1,78 | 48,8% | 258 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 872 | 935 | +€1,07 | 49,1% | 268 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 867 | 930 | +€0,48 | 47,4% | 251 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 863 | 926 | €-0,71 | 49,5% | 223 | 115 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 858 | 921 | +€5,45 | 45,3% | 208 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 858 | 921 | +€3,64 | 45,3% | 196 | 35 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 858 | 921 | +€3,62 | 43,8% | 222 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 857 | 920 | €-1,57 | 43,4% | 124 | 201 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 856 | 919 | +€2,26 | 44,9% | 172 | 59 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 848 | 911 | +€1,50 | 42,2% | 133 | 116 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 847 | 910 | €-3,17 | 35,7% | 86 | 193 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 829 | 892 | €-6,99 | 30,2% | 70 | 238 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 827 | 890 | €-4,41 | 36,3% | 75 | 233 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 826 | 889 | +€3,47 | 34,4% | 103 | 92 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 809 | 872 | €-11,45 | 29,0% | 170 | 146 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 801 | 864 | €-11,32 | 27,2% | 65 | 235 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 791 | 854 | +€0,35 | 38,2% | 63 | 146 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 749 | 812 | €-17,83 | 22,4% | 64 | 233 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
