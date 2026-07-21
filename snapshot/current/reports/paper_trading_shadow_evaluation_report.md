# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T08:38:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **3091**
- Valutazioni prodotte: **2360**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 114 | 0,052 | 0,033 | -0,055 | 55,3% | 76,3 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TIME_12H | 109 | 0,157 | 0,000 | 0,040 | 45,9% | 72,4 | VALIDATING |
| GB20_R050 | 114 | 0,219 | 0,000 | 0,074 | 47,4% | 70,0 | VALIDATING |
| GB30_R050 | 114 | 0,186 | 0,000 | 0,042 | 46,5% | 70,0 | VALIDATING |
| GB20_R100 | 114 | 0,120 | 0,000 | 0,017 | 43,0% | 69,4 | VALIDATING |
| TP_R050 | 114 | 0,143 | 0,000 | -0,022 | 47,4% | 66,8 | VALIDATING |
| TP_R100 | 114 | 0,091 | 0,000 | -0,019 | 43,0% | 66,5 | VALIDATING |
| GB50_R100 | 105 | 0,072 | 0,000 | -0,017 | 42,9% | 66,4 | VALIDATING |
| GB50_R050 | 114 | 0,143 | 0,000 | -0,001 | 46,5% | 66,0 | VALIDATING |
| GB40_R050 | 114 | 0,148 | 0,000 | -0,008 | 46,5% | 65,0 | VALIDATING |
| TP_R200 | 111 | 0,089 | 0,000 | -0,028 | 36,9% | 64,3 | VALIDATING |
| GB40_R100 | 107 | 0,065 | 0,000 | -0,032 | 43,0% | 64,3 | VALIDATING |
| GB30_R100 | 111 | 0,071 | 0,000 | -0,042 | 42,3% | 62,9 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 112 | -0,006 | 0,000 | -0,100 | 32,1% | 39,4 | VALIDATING |
| ATR20_R100 | 103 | -0,093 | 0,000 | -0,210 | 37,9% | 38,9 | VALIDATING |
| ATR15_R100 | 103 | -0,051 | 0,000 | -0,133 | 38,8% | 38,5 | VALIDATING |
| BE_R050 | 112 | -0,145 | 0,000 | -0,335 | 37,5% | 34,9 | VALIDATING |
| ATR30_R100 | 102 | -0,240 | 0,000 | -0,397 | 35,3% | 32,4 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
