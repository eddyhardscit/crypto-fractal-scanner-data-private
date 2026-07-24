# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T16:53:42+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **366**
- Scenari virtuali ancora attivi: **2879**
- Gruppi in attesa dell'uscita originale: **178**
- Gruppi con originale chiuso ma Shadow ancora attive: **188**
- Confronti completati: **17049**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 817 | 880 | +€6,57 | 50,5% | 225 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 817 | 880 | +€4,45 | 49,3% | 230 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 817 | 880 | +€2,18 | 48,1% | 236 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 817 | 880 | +€1,24 | 48,2% | 248 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 812 | 875 | +€0,87 | 46,5% | 230 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 810 | 873 | +€5,66 | 44,2% | 191 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 810 | 873 | +€3,64 | 44,2% | 179 | 35 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 810 | 873 | +€3,56 | 42,6% | 205 | 23 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 810 | 873 | €-0,77 | 49,0% | 204 | 112 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 808 | 871 | +€2,36 | 43,9% | 155 | 59 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 803 | 866 | €-2,43 | 35,0% | 79 | 178 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 800 | 863 | +€1,80 | 40,9% | 116 | 116 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 797 | 860 | €-1,73 | 43,1% | 110 | 191 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 785 | 848 | €-6,08 | 29,1% | 63 | 223 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 779 | 842 | +€2,80 | 33,0% | 95 | 91 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 758 | 821 | €-3,28 | 35,6% | 63 | 215 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 757 | 820 | €-10,46 | 26,0% | 58 | 220 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 754 | 817 | €-10,80 | 28,4% | 151 | 139 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 723 | 786 | €-1,08 | 36,0% | 50 | 136 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 705 | 768 | €-17,29 | 20,8% | 57 | 218 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
