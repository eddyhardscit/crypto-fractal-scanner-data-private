# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T05:10:21+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **88**
- Scenari virtuali ancora attivi: **1153**
- Gruppi in attesa dell'uscita originale: **70**
- Gruppi con originale chiuso ma Shadow ancora attive: **18**
- Confronti completati: **695**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 18 | 40 | +€13,57 | 50,0% | 9 | 0 | PRELIMINARY_SAMPLE |
| GB30_R050 | 18 | 40 | +€10,53 | 50,0% | 9 | 0 | PRELIMINARY_SAMPLE |
| GB40_R050 | 18 | 40 | +€8,12 | 50,0% | 9 | 0 | PRELIMINARY_SAMPLE |
| TP_R050 | 18 | 40 | +€6,79 | 50,0% | 9 | 0 | PRELIMINARY_SAMPLE |
| GB50_R050 | 18 | 40 | +€5,96 | 50,0% | 9 | 0 | PRELIMINARY_SAMPLE |
| GB20_R100 | 17 | 38 | +€9,60 | 47,4% | 8 | 1 | PRELIMINARY_SAMPLE |
| GB30_R100 | 17 | 38 | +€6,20 | 47,4% | 8 | 1 | PRELIMINARY_SAMPLE |
| TP_R100 | 17 | 38 | +€4,70 | 47,4% | 8 | 1 | PRELIMINARY_SAMPLE |
| GB40_R100 | 17 | 38 | +€2,80 | 47,4% | 7 | 2 | PRELIMINARY_SAMPLE |
| GB50_R100 | 17 | 38 | €-0,29 | 44,7% | 7 | 3 | PRELIMINARY_SAMPLE |
| BE_R050 | 16 | 34 | €-1,74 | 29,4% | 8 | 0 | PRELIMINARY_SAMPLE |
| TP_R150 | 14 | 33 | +€8,82 | 39,4% | 5 | 1 | PRELIMINARY_SAMPLE |
| ATR15_R100 | 14 | 32 | €-3,21 | 43,8% | 2 | 2 | PRELIMINARY_SAMPLE |
| TIME_6H | 14 | 36 | €-6,34 | 50,0% | 11 | 3 | PRELIMINARY_SAMPLE |
| TP_R200 | 13 | 31 | +€16,66 | 45,2% | 2 | 1 | PRELIMINARY_SAMPLE |
| BE_R100 | 13 | 27 | +€1,64 | 37,0% | 0 | 1 | PRELIMINARY_SAMPLE |
| ATR30_R100 | 13 | 28 | +€1,33 | 35,7% | 1 | 1 | PRELIMINARY_SAMPLE |
| ATR20_R100 | 13 | 30 | €-0,78 | 43,3% | 0 | 2 | PRELIMINARY_SAMPLE |
| TIME_12H | 10 | 29 | +€8,04 | 58,6% | 6 | 1 | PRELIMINARY_SAMPLE |
| TIME_24H | 10 | 25 | +€3,47 | 64,0% | 2 | 2 | PRELIMINARY_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
