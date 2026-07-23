# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T17:38:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **12238**
- Valutazioni prodotte: **3546**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R200 | 3 | 1,341 | 1,762 | 0,499 | 100,0% | 76,2 | INSUFFICIENT_DATA |
| GB20_R050 | 3 | 1,257 | 1,678 | 0,416 | 100,0% | 76,2 | INSUFFICIENT_DATA |
| GB20_R100 | 3 | 1,257 | 1,678 | 0,416 | 100,0% | 76,2 | INSUFFICIENT_DATA |
| GB30_R050 | 3 | 1,018 | 1,439 | 0,177 | 100,0% | 75,9 | INSUFFICIENT_DATA |
| GB30_R100 | 3 | 1,018 | 1,439 | 0,177 | 100,0% | 75,9 | INSUFFICIENT_DATA |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R150 | 3 | 0,842 | 1,263 | -0,000 | 66,7% | 70,6 | INSUFFICIENT_DATA |
| TIME_6H | 549 | 0,030 | 0,036 | -0,046 | 52,6% | 70,6 | VALIDATING |
| GB30_R050 | 572 | 0,091 | 0,000 | 0,024 | 44,1% | 70,1 | VALIDATING |
| GB20_R050 | 572 | 0,130 | 0,000 | 0,062 | 45,3% | 70,0 | VALIDATING |
| GB20_R100 | 563 | 0,063 | 0,000 | 0,014 | 35,2% | 69,7 | VALIDATING |
| GB40_R050 | 572 | 0,049 | 0,000 | -0,014 | 43,5% | 67,8 | VALIDATING |
| TP_R050 | 572 | 0,041 | 0,000 | -0,030 | 42,3% | 64,3 | VALIDATING |
| GB40_R050 | 3 | 0,779 | 1,200 | -0,063 | 66,7% | 61,2 | INSUFFICIENT_DATA |
| GB40_R100 | 3 | 0,779 | 1,200 | -0,063 | 66,7% | 61,2 | INSUFFICIENT_DATA |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB30_R100 | 563 | 0,030 | 0,000 | -0,019 | 34,6% | 58,2 | VALIDATING |
| TP_R100 | 3 | 0,342 | 0,763 | -0,499 | 66,7% | 55,6 | INSUFFICIENT_DATA |
| TIME_12H | 532 | 0,023 | 0,000 | -0,044 | 44,0% | 55,0 | VALIDATING |
| TP_R100 | 563 | 0,023 | 0,000 | -0,033 | 32,5% | 53,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
