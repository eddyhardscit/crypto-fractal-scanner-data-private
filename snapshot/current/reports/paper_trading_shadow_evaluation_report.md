# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-26T02:38:51+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **27688**
- Valutazioni prodotte: **10401**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R100 | 94 | 0,448 | 0,316 | 0,305 | 68,1% | 97,4 | VALIDATING |
| GB20_R075 | 94 | 0,420 | 0,298 | 0,283 | 64,9% | 97,1 | VALIDATING |
| GB30_R100 | 86 | 0,403 | 0,224 | 0,264 | 69,8% | 91,9 | VALIDATING |
| GB50_R100 | 64 | 0,401 | 0,298 | 0,257 | 67,2% | 91,3 | VALIDATING |
| GB50_R075 | 64 | 0,414 | 0,298 | 0,267 | 67,2% | 91,1 | VALIDATING |
| GB40_R100 | 72 | 0,394 | 0,270 | 0,253 | 66,7% | 89,3 | VALIDATING |
| GB30_R075 | 86 | 0,374 | 0,224 | 0,233 | 61,6% | 88,7 | VALIDATING |
| ATR15_R100 | 60 | 0,144 | 0,286 | 0,045 | 66,7% | 86,2 | VALIDATING |
| ATR20_R100 | 54 | 0,161 | 0,286 | 0,044 | 74,1% | 85,0 | VALIDATING |
| ATR30_R100 | 54 | 0,161 | 0,286 | 0,044 | 74,1% | 85,0 | VALIDATING |
| BE_A100 | 54 | 0,161 | 0,286 | 0,033 | 74,1% | 85,0 | VALIDATING |
| BE_R100 | 54 | 0,161 | 0,286 | 0,036 | 74,1% | 85,0 | VALIDATING |
| BE_A060 | 54 | 0,198 | 0,286 | 0,078 | 74,1% | 84,4 | VALIDATING |
| BE_A075 | 54 | 0,198 | 0,286 | 0,082 | 74,1% | 84,4 | VALIDATING |
| BE_R075 | 54 | 0,198 | 0,286 | 0,086 | 74,1% | 84,4 | VALIDATING |
| GB40_R075 | 72 | 0,374 | 0,275 | 0,212 | 58,3% | 82,4 | VALIDATING |
| GB20_R040 | 94 | 0,134 | 0,058 | -0,064 | 57,4% | 76,7 | VALIDATING |
| TP_R100 | 94 | 0,204 | 0,056 | 0,033 | 51,1% | 76,1 | VALIDATING |
| TP_R250 | 71 | 0,201 | 0,049 | 0,012 | 50,7% | 74,4 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
