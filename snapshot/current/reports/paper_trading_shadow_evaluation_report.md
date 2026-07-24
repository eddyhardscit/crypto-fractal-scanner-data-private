# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-24T03:53:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **15006**
- Valutazioni prodotte: **4331**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB20_R050 | 91 | 0,430 | 0,374 | 0,278 | 86,8% | 96,7 | VALIDATING |
| GB30_R050 | 91 | 0,379 | 0,301 | 0,227 | 86,8% | 96,7 | VALIDATING |
| GB20_R100 | 90 | 0,478 | 0,417 | 0,333 | 85,6% | 96,5 | VALIDATING |
| GB30_R100 | 90 | 0,445 | 0,408 | 0,323 | 88,9% | 96,5 | VALIDATING |
| TP_R100 | 90 | 0,439 | 0,413 | 0,305 | 84,4% | 96,5 | VALIDATING |
| GB40_R100 | 90 | 0,383 | 0,408 | 0,250 | 84,4% | 96,4 | VALIDATING |
| GB50_R100 | 90 | 0,331 | 0,408 | 0,220 | 82,2% | 96,1 | VALIDATING |
| GB40_R050 | 91 | 0,319 | 0,287 | 0,177 | 83,5% | 92,8 | VALIDATING |
| GB50_R050 | 91 | 0,327 | 0,287 | 0,208 | 83,5% | 92,6 | VALIDATING |
| TP_R050 | 91 | 0,238 | 0,293 | 0,091 | 83,5% | 90,6 | VALIDATING |
| BE_R050 | 83 | 0,080 | 0,129 | -0,048 | 60,2% | 78,8 | VALIDATING |
| TIME_6H | 84 | 0,049 | 0,168 | -0,102 | 65,5% | 75,8 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 621 | 0,102 | 0,000 | 0,038 | 45,1% | 70,0 | VALIDATING |
| GB20_R100 | 609 | 0,061 | 0,000 | 0,013 | 36,5% | 69,7 | VALIDATING |
| TP_R150 | 599 | 0,058 | 0,000 | 0,009 | 27,4% | 69,7 | VALIDATING |
| GB30_R050 | 621 | 0,061 | 0,000 | -0,003 | 43,5% | 69,5 | VALIDATING |
| TP_R200 | 65 | 0,038 | 0,243 | -0,125 | 72,3% | 69,5 | VALIDATING |
| BE_R100 | 82 | 0,025 | 0,129 | -0,083 | 59,8% | 66,1 | VALIDATING |
| ATR15_R100 | 90 | 0,019 | 0,104 | -0,094 | 63,3% | 64,1 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
