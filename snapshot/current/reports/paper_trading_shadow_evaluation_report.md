# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T00:53:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **13368**
- Valutazioni prodotte: **4049**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB30_R050 | 40 | 0,403 | 0,442 | 0,176 | 87,5% | 86,7 | EARLY_SIGNAL |
| GB40_R050 | 40 | 0,327 | 0,404 | 0,106 | 80,0% | 86,6 | EARLY_SIGNAL |
| GB20_R050 | 40 | 0,454 | 0,446 | 0,225 | 87,5% | 86,6 | EARLY_SIGNAL |
| TP_R100 | 39 | 0,468 | 0,477 | 0,261 | 82,1% | 86,5 | EARLY_SIGNAL |
| GB30_R100 | 39 | 0,554 | 0,477 | 0,417 | 97,4% | 86,5 | EARLY_SIGNAL |
| GB40_R100 | 39 | 0,461 | 0,477 | 0,314 | 82,1% | 86,5 | EARLY_SIGNAL |
| GB20_R100 | 39 | 0,550 | 0,477 | 0,351 | 89,7% | 86,5 | EARLY_SIGNAL |
| GB50_R050 | 40 | 0,382 | 0,369 | 0,199 | 80,0% | 86,2 | EARLY_SIGNAL |
| GB50_R100 | 39 | 0,424 | 0,416 | 0,254 | 82,1% | 86,0 | EARLY_SIGNAL |
| TP_R200 | 31 | 0,288 | 0,408 | 0,096 | 77,4% | 83,4 | EARLY_SIGNAL |
| ATR20_R100 | 35 | 0,172 | 0,322 | 0,031 | 68,6% | 82,1 | EARLY_SIGNAL |
| TIME_6H | 588 | 0,052 | 0,036 | -0,023 | 52,7% | 79,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 40 | 0,176 | 0,362 | -0,032 | 80,0% | 73,8 | EARLY_SIGNAL |
| TP_R150 | 31 | 0,143 | 0,287 | -0,020 | 58,1% | 73,4 | EARLY_SIGNAL |
| TIME_12H | 562 | 0,101 | 0,000 | 0,026 | 45,9% | 72,8 | VALIDATING |
| BE_R100 | 34 | 0,103 | 0,305 | -0,072 | 64,7% | 70,7 | EARLY_SIGNAL |
| GB30_R050 | 585 | 0,084 | 0,000 | 0,017 | 43,8% | 70,1 | VALIDATING |
| GB20_R050 | 585 | 0,124 | 0,000 | 0,051 | 45,0% | 70,0 | VALIDATING |
| ATR15_R100 | 39 | 0,103 | 0,287 | -0,061 | 61,5% | 69,8 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
