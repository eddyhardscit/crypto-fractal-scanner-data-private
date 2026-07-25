# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T15:23:58+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **21871**
- Valutazioni prodotte: **6119**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R200 | 393 | 0,187 | 0,147 | 0,087 | 53,9% | 83,6 | VALIDATING |
| GB20_R100 | 414 | 0,044 | 0,030 | -0,038 | 52,4% | 76,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 660 | 0,092 | 0,000 | 0,028 | 46,1% | 70,0 | VALIDATING |
| TP_R150 | 637 | 0,056 | 0,000 | 0,005 | 27,9% | 69,8 | VALIDATING |
| GB20_R100 | 645 | 0,065 | 0,000 | 0,015 | 37,4% | 69,8 | VALIDATING |
| GB30_R050 | 660 | 0,051 | 0,000 | -0,016 | 44,5% | 67,7 | VALIDATING |
| TP_R150 | 403 | 0,064 | 0,000 | -0,016 | 38,0% | 67,3 | VALIDATING |
| GB30_R100 | 414 | 0,017 | 0,053 | -0,064 | 53,1% | 63,9 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 645 | 0,033 | 0,000 | -0,022 | 35,2% | 58,7 | VALIDATING |
| GB30_R100 | 645 | 0,026 | 0,000 | -0,029 | 37,1% | 55,2 | VALIDATING |
| TP_R200 | 634 | 0,028 | 0,000 | -0,041 | 34,5% | 54,0 | VALIDATING |
| TP_R050 | 660 | 0,013 | 0,000 | -0,054 | 43,5% | 51,5 | VALIDATING |
| TIME_12H | 663 | 0,022 | 0,000 | -0,048 | 42,5% | 50,5 | VALIDATING |
| GB40_R050 | 660 | 0,008 | 0,000 | -0,054 | 43,6% | 49,4 | VALIDATING |
| GB40_R100 | 644 | 0,011 | 0,000 | -0,043 | 37,1% | 48,2 | VALIDATING |
| GB40_R100 | 412 | -0,042 | 0,053 | -0,123 | 51,7% | 47,8 | VALIDATING |
| GB50_R100 | 642 | 0,008 | 0,000 | -0,039 | 33,8% | 47,7 | VALIDATING |
| GB20_R050 | 422 | -0,095 | 0,039 | -0,189 | 51,4% | 47,3 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
