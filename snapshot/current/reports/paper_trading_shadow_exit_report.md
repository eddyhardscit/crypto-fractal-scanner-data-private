# Block 3 — Shadow Exit Engine

Generato: 2026-07-20T07:08:34+00:00

> Motore esclusivamente osservativo e Paper-only. Non modifica le uscite reali. I confronti escludono il funding sia dall'uscita originale sia dalle varianti.

## Stato operativo

- Gruppi di trade ancora monitorati: **91**
- Scenari virtuali ancora attivi: **1160**
- Gruppi in attesa dell'uscita originale: **71**
- Gruppi con originale chiuso ma Shadow ancora attive: **20**
- Confronti completati: **941**

## Classifica osservativa complessiva

| Scenario | Campione completo | Campione totale | Δ medio vs originale | Migliora | Troppo presto | Troppo tardi | Stato dati |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 27 | 51 | +€12,50 | 43,1% | 11 | 0 | PRELIMINARY_SAMPLE |
| GB30_R050 | 27 | 51 | +€9,84 | 43,1% | 11 | 0 | PRELIMINARY_SAMPLE |
| GB40_R050 | 27 | 51 | +€7,67 | 43,1% | 11 | 0 | PRELIMINARY_SAMPLE |
| TP_R050 | 27 | 51 | +€6,92 | 43,1% | 11 | 0 | PRELIMINARY_SAMPLE |
| GB20_R100 | 27 | 50 | +€5,96 | 38,0% | 9 | 2 | PRELIMINARY_SAMPLE |
| GB50_R050 | 27 | 51 | +€5,91 | 43,1% | 11 | 0 | PRELIMINARY_SAMPLE |
| GB30_R100 | 27 | 50 | +€3,12 | 38,0% | 9 | 2 | PRELIMINARY_SAMPLE |
| TP_R100 | 27 | 50 | +€2,14 | 38,0% | 9 | 2 | PRELIMINARY_SAMPLE |
| GB40_R100 | 27 | 50 | +€0,27 | 36,0% | 8 | 3 | PRELIMINARY_SAMPLE |
| GB50_R100 | 27 | 49 | €-2,23 | 34,7% | 8 | 4 | PRELIMINARY_SAMPLE |
| TP_R150 | 24 | 45 | +€4,22 | 28,9% | 5 | 3 | PRELIMINARY_SAMPLE |
| BE_R050 | 24 | 48 | €-3,89 | 25,0% | 9 | 4 | PRELIMINARY_SAMPLE |
| ATR15_R100 | 23 | 42 | €-3,67 | 33,3% | 2 | 3 | PRELIMINARY_SAMPLE |
| ATR20_R100 | 23 | 42 | €-4,09 | 31,0% | 0 | 5 | PRELIMINARY_SAMPLE |
| TIME_6H | 23 | 49 | €-5,52 | 38,8% | 12 | 4 | PRELIMINARY_SAMPLE |
| ATR30_R100 | 23 | 42 | €-6,62 | 23,8% | 1 | 6 | PRELIMINARY_SAMPLE |
| BE_R100 | 23 | 42 | €-6,95 | 23,8% | 0 | 7 | PRELIMINARY_SAMPLE |
| TP_R200 | 22 | 42 | +€9,88 | 33,3% | 2 | 3 | PRELIMINARY_SAMPLE |
| TIME_12H | 22 | 48 | +€3,64 | 45,8% | 7 | 4 | PRELIMINARY_SAMPLE |
| TIME_24H | 19 | 37 | +€2,52 | 45,9% | 2 | 3 | PRELIMINARY_SAMPLE |

## Come leggere il controllo

- **EARLIER_BETTER**: la variante è uscita prima e ha conservato più profitto.
- **TOO_EARLY**: la variante è uscita prima ma ha tagliato un movimento migliore.
- **LATER_BETTER**: la variante ha continuato dopo l'uscita originale e ha guadagnato di più.
- **TOO_LATE**: la variante è rimasta aperta più a lungo e ha peggiorato il risultato.

## Limiti e protezioni

Le regole Shadow mantengono entrata, quantità, commissioni, stop protettivo iniziale e liquidazione. Le ambiguità all'interno della stessa candela vengono risolte scegliendo l'esito peggiore. Le posizioni già aperte al momento dell'installazione sono marcate come campione parziale e non saranno utilizzate dal futuro Blocco 4 come prova piena.
