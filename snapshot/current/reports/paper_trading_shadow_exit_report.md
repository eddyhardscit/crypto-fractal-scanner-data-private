# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T23:08:48+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **390**
- Scenari virtuali ancora attivi: **3527**
- Gruppi in attesa dell'uscita originale: **203**
- Gruppi con originale chiuso ma Shadow ancora attive: **187**
- Confronti completati: **18493**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 894 | 957 | +€5,13 | 50,6% | 262 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 894 | 957 | +€2,95 | 49,5% | 267 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 894 | 957 | +€0,65 | 48,2% | 274 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 894 | 957 | €-0,03 | 48,5% | 285 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 893 | 956 | €-2,06 | 48,8% | 238 | 121 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 887 | 950 | €-0,64 | 46,9% | 266 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 878 | 941 | +€4,60 | 44,7% | 223 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 878 | 941 | +€2,85 | 43,3% | 237 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 878 | 941 | +€2,74 | 44,7% | 211 | 35 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 875 | 938 | +€1,44 | 44,3% | 186 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 874 | 937 | €-2,29 | 42,8% | 138 | 201 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 866 | 929 | +€0,64 | 41,7% | 147 | 116 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 854 | 917 | €-3,47 | 35,7% | 90 | 193 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 848 | 911 | +€3,34 | 34,2% | 117 | 92 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 847 | 910 | €-7,39 | 30,3% | 75 | 243 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 837 | 900 | €-4,76 | 36,1% | 80 | 235 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 830 | 893 | +€2,43 | 39,4% | 69 | 146 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 825 | 888 | €-12,71 | 28,6% | 184 | 146 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 819 | 882 | €-11,67 | 26,6% | 70 | 240 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 767 | 830 | €-18,06 | 21,9% | 69 | 238 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
