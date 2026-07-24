# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T15:53:48+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **16889**
- Valutazioni prodotte: **4865**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 160 | 0,386 | 0,332 | 0,265 | 74,4% | 98,7 | ELIGIBLE_FOR_MUTATION |
| GB30_R050 | 160 | 0,332 | 0,286 | 0,224 | 74,4% | 98,7 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 159 | 0,374 | 0,322 | 0,243 | 73,6% | 94,9 | VALIDATING |
| TP_R100 | 159 | 0,339 | 0,287 | 0,228 | 73,0% | 94,9 | VALIDATING |
| GB30_R100 | 159 | 0,331 | 0,287 | 0,214 | 75,5% | 94,9 | VALIDATING |
| GB40_R050 | 160 | 0,274 | 0,241 | 0,167 | 72,5% | 94,8 | VALIDATING |
| GB40_R100 | 158 | 0,279 | 0,287 | 0,175 | 73,4% | 94,8 | VALIDATING |
| GB50_R050 | 159 | 0,266 | 0,217 | 0,174 | 71,7% | 94,7 | VALIDATING |
| GB50_R100 | 157 | 0,224 | 0,287 | 0,111 | 72,0% | 94,6 | VALIDATING |
| TP_R050 | 160 | 0,209 | 0,273 | 0,111 | 72,5% | 93,4 | VALIDATING |
| TP_R150 | 142 | 0,149 | 0,104 | 0,014 | 57,7% | 87,5 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 642 | 0,096 | 0,000 | 0,032 | 45,3% | 70,0 | VALIDATING |
| TP_R150 | 625 | 0,063 | 0,000 | 0,011 | 28,0% | 69,8 | VALIDATING |
| GB20_R100 | 636 | 0,069 | 0,000 | 0,023 | 37,3% | 69,7 | VALIDATING |
| GB30_R050 | 642 | 0,056 | 0,000 | -0,010 | 43,8% | 68,5 | VALIDATING |
| TIME_6H | 157 | 0,045 | 0,039 | -0,088 | 52,9% | 65,2 | VALIDATING |
| GB30_R100 | 636 | 0,031 | 0,000 | -0,021 | 36,9% | 61,9 | VALIDATING |
| TP_R100 | 636 | 0,036 | 0,000 | -0,018 | 35,1% | 60,2 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
