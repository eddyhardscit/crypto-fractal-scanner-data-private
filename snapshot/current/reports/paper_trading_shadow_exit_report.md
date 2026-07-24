# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T15:53:47+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **347**
- Scenari virtuali ancora attivi: **2642**
- Gruppi in attesa dell'uscita originale: **165**
- Gruppi con originale chiuso ma Shadow ancora attive: **182**
- Confronti completati: **16889**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 808 | 871 | +€6,71 | 50,2% | 223 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 808 | 871 | +€4,58 | 49,0% | 228 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 808 | 871 | +€2,30 | 47,8% | 234 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 808 | 871 | +€1,32 | 47,9% | 246 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 808 | 871 | €-0,59 | 49,1% | 202 | 112 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 803 | 866 | +€0,99 | 46,2% | 228 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 801 | 864 | +€5,81 | 44,0% | 189 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 801 | 864 | +€3,79 | 44,0% | 177 | 34 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 801 | 864 | +€3,70 | 42,4% | 203 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 799 | 862 | +€2,52 | 43,6% | 153 | 58 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 796 | 859 | €-2,37 | 35,3% | 79 | 177 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 793 | 856 | +€1,88 | 40,5% | 116 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 789 | 852 | €-1,58 | 43,0% | 108 | 190 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 778 | 841 | €-6,05 | 29,4% | 63 | 222 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 773 | 836 | +€3,01 | 33,1% | 95 | 88 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 750 | 813 | €-10,47 | 26,2% | 58 | 219 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 746 | 809 | €-10,82 | 28,6% | 150 | 139 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 744 | 807 | €-3,27 | 34,9% | 62 | 212 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 717 | 780 | €-1,05 | 35,9% | 50 | 133 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 698 | 761 | €-17,35 | 21,0% | 57 | 217 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
