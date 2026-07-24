# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T11:03:06+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **345**
- Scenari virtuali ancora attivi: **2839**
- Gruppi in attesa dell'uscita originale: **181**
- Gruppi con originale chiuso ma Shadow ancora attive: **164**
- Confronti completati: **15753**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 752 | 815 | +€7,18 | 50,1% | 200 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 752 | 815 | +€5,04 | 48,8% | 205 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 752 | 815 | +€2,75 | 47,5% | 211 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 752 | 815 | +€1,62 | 47,6% | 223 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 749 | 812 | +€1,41 | 45,8% | 206 | 27 | READY_FOR_BLOCK4_EVALUATION |
| TIME_6H | 742 | 805 | €-0,90 | 49,7% | 166 | 112 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 738 | 801 | €-0,49 | 42,9% | 85 | 187 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 737 | 800 | +€5,89 | 43,1% | 169 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 737 | 800 | +€3,93 | 43,0% | 158 | 34 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 737 | 800 | +€3,78 | 41,2% | 184 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 736 | 799 | +€2,69 | 42,6% | 135 | 58 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 736 | 799 | €-1,46 | 34,2% | 61 | 175 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 733 | 796 | +€2,28 | 39,3% | 99 | 115 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 732 | 795 | €-5,14 | 29,8% | 44 | 221 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 705 | 768 | €-9,77 | 26,4% | 40 | 218 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 699 | 762 | +€1,38 | 30,7% | 78 | 88 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 696 | 759 | €-10,51 | 28,7% | 125 | 138 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 684 | 747 | €-4,00 | 33,6% | 46 | 207 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 671 | 734 | €-0,04 | 35,8% | 36 | 131 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 653 | 716 | €-17,04 | 20,9% | 39 | 216 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
