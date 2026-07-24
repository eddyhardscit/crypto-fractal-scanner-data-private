# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T05:53:44+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **15126**
- Valutazioni prodotte: **4339**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB40_R050 | 96 | 0,317 | 0,287 | 0,183 | 82,3% | 97,6 | VALIDATING |
| GB20_R050 | 96 | 0,425 | 0,366 | 0,276 | 85,4% | 97,5 | VALIDATING |
| GB50_R050 | 96 | 0,323 | 0,287 | 0,204 | 81,2% | 97,4 | VALIDATING |
| GB30_R050 | 96 | 0,375 | 0,301 | 0,231 | 85,4% | 97,4 | VALIDATING |
| GB20_R100 | 94 | 0,458 | 0,408 | 0,330 | 84,0% | 97,3 | VALIDATING |
| TP_R100 | 94 | 0,421 | 0,369 | 0,290 | 83,0% | 97,2 | VALIDATING |
| GB40_R100 | 94 | 0,367 | 0,326 | 0,248 | 83,0% | 97,2 | VALIDATING |
| GB30_R100 | 94 | 0,427 | 0,333 | 0,307 | 87,2% | 97,0 | VALIDATING |
| GB50_R100 | 94 | 0,317 | 0,369 | 0,205 | 80,9% | 96,9 | VALIDATING |
| TP_R050 | 96 | 0,242 | 0,287 | 0,109 | 82,3% | 95,5 | VALIDATING |
| BE_R050 | 87 | 0,089 | 0,129 | -0,035 | 59,8% | 77,4 | VALIDATING |
| TIME_6H | 88 | 0,047 | 0,149 | -0,095 | 64,8% | 77,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 71 | 0,048 | 0,217 | -0,098 | 71,8% | 73,6 | VALIDATING |
| GB20_R050 | 622 | 0,102 | 0,000 | 0,034 | 45,2% | 70,0 | VALIDATING |
| GB20_R100 | 610 | 0,062 | 0,000 | 0,013 | 36,6% | 69,7 | VALIDATING |
| GB30_R050 | 622 | 0,062 | 0,000 | -0,002 | 43,6% | 69,7 | VALIDATING |
| TP_R150 | 599 | 0,058 | 0,000 | 0,009 | 27,4% | 69,7 | VALIDATING |
| ATR15_R100 | 94 | 0,019 | 0,104 | -0,093 | 62,8% | 63,9 | VALIDATING |
| BE_R100 | 86 | 0,024 | 0,104 | -0,086 | 59,3% | 62,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
