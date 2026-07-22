# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-22T19:23:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **10161**
- Valutazioni prodotte: **3283**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 462 | 0,118 | 0,000 | 0,046 | 46,5% | 73,8 | VALIDATING |
| GB30_R050 | 462 | 0,158 | 0,000 | 0,091 | 47,0% | 73,8 | VALIDATING |
| GB40_R050 | 462 | 0,119 | 0,000 | 0,048 | 46,5% | 73,8 | VALIDATING |
| GB20_R050 | 462 | 0,193 | 0,000 | 0,115 | 48,3% | 73,7 | VALIDATING |
| GB20_R100 | 454 | 0,109 | 0,000 | 0,058 | 37,9% | 73,5 | VALIDATING |
| GB30_R100 | 454 | 0,084 | 0,000 | 0,034 | 37,4% | 73,5 | VALIDATING |
| GB40_R100 | 454 | 0,061 | 0,000 | 0,010 | 37,4% | 73,3 | VALIDATING |
| GB50_R100 | 452 | 0,045 | 0,000 | -0,005 | 35,2% | 72,3 | VALIDATING |
| TP_R100 | 455 | 0,077 | 0,000 | 0,023 | 36,0% | 69,8 | VALIDATING |
| TP_R150 | 426 | 0,063 | 0,000 | 0,005 | 28,2% | 69,4 | VALIDATING |
| TIME_12H | 438 | 0,062 | 0,000 | -0,013 | 45,7% | 66,9 | VALIDATING |
| GB50_R050 | 462 | 0,076 | 0,000 | 0,010 | 45,9% | 66,1 | VALIDATING |
| TIME_6H | 461 | 0,016 | 0,036 | -0,062 | 52,9% | 63,8 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R200 | 397 | -0,002 | 0,000 | -0,075 | 31,5% | 42,8 | VALIDATING |
| ATR15_R100 | 446 | -0,040 | 0,000 | -0,086 | 28,9% | 33,2 | VALIDATING |
| BE_R050 | 418 | -0,080 | 0,000 | -0,158 | 29,4% | 32,2 | UNDERPERFORMING |
| ATR20_R100 | 440 | -0,087 | 0,000 | -0,141 | 24,1% | 31,0 | UNDERPERFORMING |
| ATR30_R100 | 426 | -0,104 | 0,000 | -0,172 | 23,9% | 31,0 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
