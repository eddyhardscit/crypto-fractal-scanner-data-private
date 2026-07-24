# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T13:54:13+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **346**
- Scenari virtuali ancora attivi: **2603**
- Gruppi in attesa dell'uscita originale: **182**
- Gruppi con originale chiuso ma Shadow ancora attive: **164**
- Confronti completati: **16201**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 773 | 836 | +€0,28 | 50,2% | 177 | 112 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 770 | 833 | +€7,09 | 49,8% | 210 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 770 | 833 | +€4,95 | 48,6% | 215 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 770 | 833 | +€2,65 | 47,3% | 221 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 770 | 833 | +€1,68 | 47,4% | 233 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 767 | 830 | +€1,28 | 45,5% | 217 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 763 | 826 | +€5,68 | 43,0% | 179 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 763 | 826 | +€3,67 | 42,9% | 168 | 34 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 763 | 826 | +€3,47 | 41,2% | 194 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 762 | 825 | +€2,46 | 42,5% | 144 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 759 | 822 | +€1,94 | 39,4% | 108 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 756 | 819 | €-1,19 | 42,9% | 94 | 189 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 752 | 815 | +€3,82 | 33,3% | 86 | 88 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 750 | 813 | €-2,16 | 33,7% | 68 | 175 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 745 | 808 | €-5,72 | 29,5% | 50 | 221 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 718 | 781 | €-10,30 | 26,1% | 46 | 218 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 715 | 778 | €-2,97 | 34,6% | 54 | 208 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 712 | 775 | €-10,51 | 28,9% | 133 | 139 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 697 | 760 | €-0,25 | 36,2% | 42 | 133 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 666 | 729 | €-17,47 | 20,7% | 45 | 216 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
