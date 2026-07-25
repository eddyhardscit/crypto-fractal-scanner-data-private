# Block 3 — Shadow Exit Engine

Generato: 2026-07-25T01:08:51+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **421**
- Scenari virtuali ancora attivi: **4061**
- Gruppi in attesa dell'uscita originale: **228**
- Gruppi con originale chiuso ma Shadow ancora attive: **193**
- Confronti completati: **18570**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 900 | 963 | +€5,22 | 50,9% | 262 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 900 | 963 | +€3,03 | 49,5% | 270 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 900 | 963 | +€0,71 | 48,2% | 277 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 900 | 963 | +€0,03 | 48,8% | 285 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 900 | 963 | €-2,00 | 49,1% | 238 | 122 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 894 | 957 | €-0,58 | 47,0% | 269 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 884 | 947 | +€4,76 | 45,1% | 223 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 884 | 947 | +€3,05 | 43,6% | 237 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 884 | 947 | +€2,88 | 45,1% | 211 | 35 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 881 | 944 | +€1,55 | 44,7% | 186 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 877 | 940 | €-2,30 | 42,8% | 138 | 202 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 872 | 935 | +€0,72 | 42,0% | 147 | 116 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 855 | 918 | €-3,47 | 35,6% | 90 | 193 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 848 | 911 | +€3,34 | 34,2% | 117 | 92 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 848 | 911 | €-7,39 | 30,3% | 75 | 243 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 837 | 900 | €-4,76 | 36,1% | 80 | 235 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 830 | 893 | +€2,43 | 39,4% | 69 | 146 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 827 | 890 | €-12,70 | 28,5% | 184 | 147 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 820 | 883 | €-11,65 | 26,6% | 70 | 240 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 768 | 831 | €-18,03 | 21,9% | 69 | 238 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
