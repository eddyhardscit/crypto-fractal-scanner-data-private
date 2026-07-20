# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T06:08:35+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **92**
- Scenari virtuali ancora attivi: **1175**
- Gruppi in attesa dell'uscita originale: **73**
- Gruppi con originale chiuso ma Shadow ancora attive: **19**
- Confronti completati: **743**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 20 | 42 | +€11,81 | 47,6% | 10 | 0 | PRELIMINARY_SAMPLE |
| GB30_R050 | 20 | 42 | +€8,83 | 47,6% | 10 | 0 | PRELIMINARY_SAMPLE |
| GB40_R050 | 20 | 42 | +€6,45 | 47,6% | 10 | 0 | PRELIMINARY_SAMPLE |
| TP_R050 | 20 | 42 | +€5,27 | 47,6% | 10 | 0 | PRELIMINARY_SAMPLE |
| GB50_R050 | 20 | 42 | +€4,56 | 47,6% | 10 | 0 | PRELIMINARY_SAMPLE |
| GB20_R100 | 19 | 40 | +€8,37 | 45,0% | 9 | 1 | PRELIMINARY_SAMPLE |
| GB30_R100 | 19 | 40 | +€5,00 | 45,0% | 9 | 1 | PRELIMINARY_SAMPLE |
| TP_R100 | 19 | 40 | +€3,84 | 45,0% | 9 | 1 | PRELIMINARY_SAMPLE |
| GB40_R100 | 19 | 40 | +€1,63 | 45,0% | 8 | 2 | PRELIMINARY_SAMPLE |
| GB50_R100 | 19 | 40 | €-1,44 | 42,5% | 8 | 3 | PRELIMINARY_SAMPLE |
| BE_R050 | 17 | 39 | €-6,25 | 25,6% | 8 | 4 | PRELIMINARY_SAMPLE |
| TP_R150 | 16 | 35 | +€8,32 | 37,1% | 5 | 1 | PRELIMINARY_SAMPLE |
| ATR15_R100 | 15 | 33 | €-3,11 | 42,4% | 2 | 2 | PRELIMINARY_SAMPLE |
| ATR20_R100 | 15 | 33 | €-3,65 | 39,4% | 0 | 4 | PRELIMINARY_SAMPLE |
| TIME_6H | 15 | 37 | €-6,17 | 48,6% | 11 | 3 | PRELIMINARY_SAMPLE |
| ATR30_R100 | 15 | 33 | €-6,87 | 30,3% | 1 | 5 | PRELIMINARY_SAMPLE |
| TP_R200 | 14 | 32 | +€16,14 | 43,8% | 2 | 1 | PRELIMINARY_SAMPLE |
| BE_R100 | 14 | 32 | €-4,39 | 31,2% | 0 | 5 | PRELIMINARY_SAMPLE |
| TIME_12H | 11 | 33 | +€9,39 | 60,6% | 6 | 1 | PRELIMINARY_SAMPLE |
| TIME_24H | 11 | 26 | +€3,34 | 61,5% | 2 | 2 | PRELIMINARY_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
