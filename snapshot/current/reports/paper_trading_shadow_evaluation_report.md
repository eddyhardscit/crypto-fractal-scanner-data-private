# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T07:38:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **3035**
- Valutazioni prodotte: **2360**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 113 | 0,070 | 0,033 | -0,033 | 55,8% | 80,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TIME_12H | 108 | 0,168 | 0,000 | 0,055 | 46,3% | 72,4 | VALIDATING |
| GB20_R050 | 113 | 0,233 | 0,000 | 0,089 | 47,8% | 70,0 | VALIDATING |
| GB30_R050 | 113 | 0,200 | 0,000 | 0,041 | 46,9% | 70,0 | VALIDATING |
| GB40_R050 | 113 | 0,162 | 0,000 | 0,013 | 46,9% | 70,0 | VALIDATING |
| GB50_R050 | 113 | 0,158 | 0,000 | 0,020 | 46,9% | 69,9 | VALIDATING |
| GB20_R100 | 113 | 0,131 | 0,000 | 0,022 | 43,4% | 69,4 | VALIDATING |
| TP_R050 | 113 | 0,158 | 0,000 | -0,005 | 47,8% | 69,2 | VALIDATING |
| TP_R100 | 113 | 0,100 | 0,000 | -0,009 | 43,4% | 68,0 | VALIDATING |
| GB50_R100 | 105 | 0,072 | 0,000 | -0,017 | 42,9% | 66,4 | VALIDATING |
| GB40_R100 | 107 | 0,065 | 0,000 | -0,032 | 43,0% | 64,3 | VALIDATING |
| GB30_R100 | 111 | 0,071 | 0,000 | -0,042 | 42,3% | 62,9 | VALIDATING |
| TP_R200 | 106 | 0,046 | 0,000 | -0,056 | 35,8% | 60,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TIME_24H | 96 | 0,042 | 0,000 | -0,100 | 36,5% | 47,4 | VALIDATING |
| BE_R050 | 106 | 0,014 | 0,000 | -0,122 | 39,6% | 40,7 | VALIDATING |
| TP_R150 | 111 | -0,001 | 0,000 | -0,102 | 32,4% | 39,4 | VALIDATING |
| ATR20_R100 | 103 | -0,093 | 0,000 | -0,210 | 37,9% | 38,9 | VALIDATING |
| ATR15_R100 | 103 | -0,051 | 0,000 | -0,133 | 38,8% | 38,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
