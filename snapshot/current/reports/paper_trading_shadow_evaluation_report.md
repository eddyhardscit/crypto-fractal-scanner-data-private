# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T18:08:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **17318**
- Valutazioni prodotte: **5043**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 186 | 0,260 | 0,287 | 0,144 | 68,3% | 94,9 | VALIDATING |
| TP_R100 | 186 | 0,233 | 0,248 | 0,109 | 66,7% | 94,8 | VALIDATING |
| GB20_R100 | 185 | 0,257 | 0,258 | 0,128 | 67,0% | 94,8 | VALIDATING |
| GB30_R050 | 186 | 0,204 | 0,256 | 0,092 | 68,3% | 94,8 | VALIDATING |
| GB30_R100 | 179 | 0,229 | 0,258 | 0,110 | 70,4% | 94,8 | VALIDATING |
| GB40_R100 | 178 | 0,171 | 0,243 | 0,051 | 68,5% | 94,7 | VALIDATING |
| GB40_R050 | 186 | 0,143 | 0,217 | 0,033 | 66,1% | 94,7 | VALIDATING |
| GB50_R050 | 184 | 0,130 | 0,168 | 0,028 | 65,8% | 94,5 | VALIDATING |
| GB50_R100 | 175 | 0,121 | 0,253 | -0,002 | 68,0% | 94,4 | VALIDATING |
| TP_R050 | 186 | 0,093 | 0,254 | -0,008 | 66,7% | 92,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 144 | 0,090 | 0,104 | -0,092 | 58,3% | 73,8 | VALIDATING |
| GB20_R050 | 642 | 0,096 | 0,000 | 0,032 | 45,3% | 70,0 | VALIDATING |
| TP_R150 | 626 | 0,065 | 0,000 | 0,015 | 28,1% | 69,8 | VALIDATING |
| GB20_R100 | 636 | 0,069 | 0,000 | 0,023 | 37,3% | 69,7 | VALIDATING |
| GB30_R050 | 642 | 0,056 | 0,000 | -0,010 | 43,8% | 68,5 | VALIDATING |
| TP_R150 | 166 | 0,079 | 0,038 | -0,071 | 51,2% | 66,5 | VALIDATING |
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
