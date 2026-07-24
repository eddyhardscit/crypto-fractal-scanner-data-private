# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T01:53:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **13915**
- Valutazioni prodotte: **4138**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R100 | 51 | 0,449 | 0,477 | 0,272 | 80,4% | 88,8 | VALIDATING |
| GB30_R100 | 51 | 0,503 | 0,477 | 0,352 | 92,2% | 88,7 | VALIDATING |
| GB20_R100 | 51 | 0,526 | 0,477 | 0,358 | 86,3% | 88,7 | VALIDATING |
| GB40_R100 | 51 | 0,425 | 0,477 | 0,288 | 80,4% | 88,6 | VALIDATING |
| GB30_R050 | 52 | 0,351 | 0,442 | 0,141 | 84,6% | 85,1 | VALIDATING |
| GB40_R050 | 52 | 0,272 | 0,404 | 0,075 | 78,8% | 85,0 | VALIDATING |
| GB20_R050 | 52 | 0,410 | 0,446 | 0,196 | 84,6% | 85,0 | VALIDATING |
| GB50_R050 | 52 | 0,310 | 0,369 | 0,130 | 78,8% | 84,7 | VALIDATING |
| GB50_R100 | 48 | 0,403 | 0,416 | 0,244 | 83,3% | 84,4 | EARLY_SIGNAL |
| TP_R200 | 34 | 0,259 | 0,326 | 0,074 | 76,5% | 84,0 | EARLY_SIGNAL |
| ATR20_R100 | 43 | 0,142 | 0,287 | 0,030 | 60,5% | 79,2 | EARLY_SIGNAL |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R050 | 52 | 0,127 | 0,362 | -0,052 | 78,8% | 74,0 | VALIDATING |
| GB20_R050 | 607 | 0,097 | 0,000 | 0,030 | 44,2% | 70,0 | VALIDATING |
| GB20_R100 | 601 | 0,053 | 0,000 | 0,005 | 35,6% | 69,8 | VALIDATING |
| TP_R150 | 595 | 0,051 | 0,000 | 0,002 | 26,9% | 69,7 | VALIDATING |
| TIME_12H | 595 | 0,073 | 0,000 | 0,001 | 44,4% | 69,0 | VALIDATING |
| GB30_R050 | 607 | 0,057 | 0,000 | -0,007 | 42,8% | 69,0 | VALIDATING |
| BE_R100 | 42 | 0,085 | 0,273 | -0,061 | 57,1% | 66,4 | EARLY_SIGNAL |
| BE_R050 | 42 | 0,085 | 0,273 | -0,063 | 57,1% | 66,2 | EARLY_SIGNAL |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
