# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T18:23:51+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **23395**
- Valutazioni prodotte: **6545**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 440 | 0,146 | 0,000 | 0,061 | 49,5% | 69,7 | VALIDATING |
| GB20_R050 | 665 | 0,107 | 0,000 | 0,043 | 46,2% | 69,6 | VALIDATING |
| GB30_R050 | 665 | 0,067 | 0,000 | -0,001 | 44,7% | 69,5 | VALIDATING |
| GB20_R100 | 651 | 0,079 | 0,000 | 0,024 | 37,5% | 65,5 | VALIDATING |
| TP_R150 | 449 | 0,067 | 0,000 | -0,004 | 36,1% | 65,3 | VALIDATING |
| TP_R150 | 646 | 0,051 | 0,000 | -0,002 | 28,0% | 65,1 | VALIDATING |
| TP_R100 | 651 | 0,048 | 0,000 | -0,009 | 35,3% | 64,1 | VALIDATING |
| TIME_12H | 667 | 0,047 | 0,000 | -0,030 | 42,9% | 60,6 | VALIDATING |
| GB30_R100 | 651 | 0,040 | 0,000 | -0,021 | 37,2% | 60,5 | VALIDATING |
| TP_R050 | 665 | 0,030 | 0,000 | -0,040 | 43,6% | 58,8 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB20_R100 | 463 | 0,047 | 0,000 | -0,025 | 49,5% | 58,6 | VALIDATING |
| GB40_R050 | 665 | 0,024 | 0,000 | -0,043 | 43,8% | 56,0 | VALIDATING |
| GB40_R100 | 650 | 0,025 | 0,000 | -0,035 | 37,2% | 53,3 | VALIDATING |
| GB30_R100 | 463 | 0,019 | 0,021 | -0,055 | 50,1% | 52,6 | VALIDATING |
| GB50_R100 | 649 | 0,021 | 0,000 | -0,036 | 33,9% | 51,8 | VALIDATING |
| TP_R200 | 643 | 0,023 | 0,000 | -0,049 | 34,5% | 51,0 | VALIDATING |
| TIME_6H | 667 | 0,020 | 0,000 | -0,055 | 50,1% | 49,4 | VALIDATING |
| GB20_R050 | 471 | -0,027 | 0,038 | -0,122 | 52,2% | 44,4 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
