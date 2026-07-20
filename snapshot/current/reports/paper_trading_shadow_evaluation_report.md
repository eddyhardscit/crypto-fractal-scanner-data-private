# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-20T06:08:35+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **743**
- Valutazioni prodotte: **1234**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 15 | 0,761 | 0,683 | 0,358 | 73,3% | 81,7 | INSUFFICIENT_DATA |
| GB50_R050 | 15 | 0,653 | 0,606 | 0,282 | 73,3% | 81,7 | INSUFFICIENT_DATA |
| GB30_R050 | 15 | 0,708 | 0,597 | 0,312 | 73,3% | 81,7 | INSUFFICIENT_DATA |
| TP_R100 | 14 | 0,226 | 0,033 | 0,010 | 71,4% | 80,1 | INSUFFICIENT_DATA |
| GB20_R100 | 14 | 0,211 | 0,033 | -0,008 | 71,4% | 78,9 | INSUFFICIENT_DATA |
| TP_R050 | 15 | 0,708 | 0,500 | 0,328 | 73,3% | 77,9 | INSUFFICIENT_DATA |
| GB40_R050 | 15 | 0,656 | 0,512 | 0,244 | 73,3% | 77,9 | INSUFFICIENT_DATA |
| GB30_R100 | 14 | 0,177 | 0,033 | -0,024 | 71,4% | 76,5 | INSUFFICIENT_DATA |
| TP_R150 | 11 | 0,061 | 0,033 | 0,016 | 63,6% | 75,8 | INSUFFICIENT_DATA |
| TIME_12H | 10 | 0,067 | 0,033 | 0,017 | 70,0% | 73,2 | INSUFFICIENT_DATA |
| TIME_24H | 10 | 0,067 | 0,033 | 0,017 | 70,0% | 73,2 | INSUFFICIENT_DATA |
| TIME_6H | 10 | 0,067 | 0,033 | 0,017 | 70,0% | 73,2 | INSUFFICIENT_DATA |
| TP_R200 | 10 | 0,067 | 0,033 | 0,017 | 70,0% | 73,2 | INSUFFICIENT_DATA |
| GB40_R100 | 14 | 0,143 | 0,033 | -0,063 | 71,4% | 70,8 | INSUFFICIENT_DATA |
| GB50_R100 | 14 | 0,109 | 0,033 | -0,098 | 71,4% | 65,6 | INSUFFICIENT_DATA |
| ATR15_R100 | 13 | 0,051 | 0,033 | 0,010 | 53,8% | 62,7 | INSUFFICIENT_DATA |
| ATR20_R100 | 13 | 0,051 | 0,033 | 0,012 | 53,8% | 62,7 | INSUFFICIENT_DATA |
| ATR30_R100 | 13 | 0,051 | 0,033 | 0,012 | 53,8% | 62,7 | INSUFFICIENT_DATA |
| BE_R100 | 13 | 0,051 | 0,033 | 0,010 | 53,8% | 62,7 | INSUFFICIENT_DATA |
| BE_R050 | 14 | 0,473 | 0,214 | 0,218 | 50,0% | 58,7 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
