# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T18:08:41+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **372**
- Scenari virtuali ancora attivi: **2894**
- Gruppi in attesa dell'uscita originale: **173**
- Gruppi con originale chiuso ma Shadow ancora attive: **199**
- Confronti completati: **17318**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 834 | 897 | +€5,59 | 49,6% | 241 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 834 | 897 | +€3,44 | 48,5% | 246 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 834 | 897 | +€1,14 | 47,2% | 253 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 834 | 897 | +€0,24 | 47,4% | 264 | 0 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 828 | 891 | +€2,70 | 42,0% | 221 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 828 | 891 | €-0,18 | 45,7% | 246 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 827 | 890 | +€4,69 | 43,5% | 207 | 23 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 821 | 884 | +€2,79 | 43,7% | 190 | 35 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 821 | 884 | €-1,37 | 48,4% | 214 | 113 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 819 | 882 | +€1,48 | 43,3% | 166 | 59 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 813 | 876 | €-0,82 | 43,6% | 115 | 191 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 811 | 874 | +€0,86 | 40,4% | 127 | 116 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 807 | 870 | €-2,96 | 34,8% | 83 | 178 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 798 | 861 | +€2,55 | 32,6% | 101 | 91 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 789 | 852 | €-6,60 | 29,0% | 67 | 223 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 769 | 832 | €-3,63 | 35,8% | 66 | 217 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 764 | 827 | €-11,60 | 28,1% | 161 | 139 | READY_FOR_BLOCK4_EVALUATION |
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
