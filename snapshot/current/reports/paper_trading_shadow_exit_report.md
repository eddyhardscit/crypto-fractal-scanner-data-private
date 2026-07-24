# Block 3 — Shadow Exit Engine

Generato: 2026-07-24T14:53:44+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **345**
- Scenari virtuali ancora attivi: **2654**
- Gruppi in attesa dell'uscita originale: **180**
- Gruppi con originale chiuso ma Shadow ancora attive: **165**
- Confronti completati: **16420**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 783 | 846 | +€0,11 | 50,0% | 182 | 112 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R050 | 781 | 844 | +€6,87 | 49,6% | 215 | 1 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R050 | 781 | 844 | +€4,77 | 48,5% | 220 | 8 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R050 | 781 | 844 | +€2,48 | 47,2% | 226 | 13 | READY_FOR_BLOCK4_EVALUATION |
| TP_R050 | 781 | 844 | +€1,53 | 47,3% | 238 | 0 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R050 | 777 | 840 | +€1,21 | 45,5% | 221 | 27 | READY_FOR_BLOCK4_EVALUATION |
| GB20_R100 | 774 | 837 | +€5,61 | 42,9% | 184 | 22 | READY_FOR_BLOCK4_EVALUATION |
| TP_R100 | 774 | 837 | +€3,47 | 41,2% | 198 | 22 | READY_FOR_BLOCK4_EVALUATION |
| GB30_R100 | 773 | 836 | +€3,61 | 42,8% | 172 | 34 | READY_FOR_BLOCK4_EVALUATION |
| GB40_R100 | 771 | 834 | +€2,45 | 42,6% | 147 | 58 | READY_FOR_BLOCK4_EVALUATION |
| GB50_R100 | 768 | 831 | +€1,91 | 39,5% | 111 | 115 | READY_FOR_BLOCK4_EVALUATION |
| TIME_12H | 766 | 829 | €-1,34 | 42,7% | 99 | 189 | READY_FOR_BLOCK4_EVALUATION |
| TP_R150 | 762 | 825 | +€3,46 | 33,0% | 90 | 88 | READY_FOR_BLOCK4_EVALUATION |
| ATR15_R100 | 762 | 825 | €-2,14 | 33,8% | 71 | 176 | READY_FOR_BLOCK4_EVALUATION |
| ATR20_R100 | 757 | 820 | €-5,69 | 29,6% | 53 | 222 | READY_FOR_BLOCK4_EVALUATION |
| TIME_24H | 732 | 795 | €-2,80 | 34,8% | 57 | 211 | READY_FOR_BLOCK4_EVALUATION |
| ATR30_R100 | 730 | 793 | €-10,22 | 26,4% | 49 | 219 | READY_FOR_BLOCK4_EVALUATION |
| BE_R050 | 722 | 785 | €-10,58 | 28,9% | 137 | 139 | READY_FOR_BLOCK4_EVALUATION |
| TP_R200 | 707 | 770 | €-0,57 | 35,8% | 45 | 133 | READY_FOR_BLOCK4_EVALUATION |
| BE_R100 | 678 | 741 | €-17,27 | 21,1% | 48 | 217 | READY_FOR_BLOCK4_EVALUATION |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
