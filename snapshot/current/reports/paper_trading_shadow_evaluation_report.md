# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T16:38:44+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **12177**
- Valutazioni prodotte: **3504**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R200 | 3 | 1,341 | 1,762 | 0,499 | 100,0% | 76,2 | INSUFFICIENT_DATA |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 568 | 0,140 | 0,000 | 0,071 | 45,4% | 73,8 | VALIDATING |
| GB20_R100 | 560 | 0,070 | 0,000 | 0,021 | 35,4% | 73,4 | VALIDATING |
| TIME_6H | 546 | 0,032 | 0,036 | -0,044 | 52,7% | 71,6 | VALIDATING |
| TP_R150 | 3 | 0,842 | 1,263 | -0,000 | 66,7% | 70,6 | INSUFFICIENT_DATA |
| GB30_R050 | 568 | 0,101 | 0,000 | 0,029 | 44,2% | 70,1 | VALIDATING |
| GB40_R050 | 568 | 0,059 | 0,000 | -0,003 | 43,7% | 69,6 | VALIDATING |
| TP_R050 | 568 | 0,051 | 0,000 | -0,019 | 42,4% | 67,2 | VALIDATING |
| GB30_R100 | 560 | 0,038 | 0,000 | -0,009 | 34,8% | 62,2 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TIME_12H | 531 | 0,029 | 0,000 | -0,034 | 44,1% | 58,6 | VALIDATING |
| TP_R100 | 560 | 0,030 | 0,000 | -0,025 | 32,7% | 57,3 | VALIDATING |
| TP_R150 | 547 | 0,025 | 0,000 | -0,022 | 25,0% | 55,7 | VALIDATING |
| TP_R100 | 3 | 0,342 | 0,763 | -0,499 | 66,7% | 55,6 | INSUFFICIENT_DATA |
| GB50_R050 | 562 | 0,024 | 0,000 | -0,045 | 41,8% | 52,5 | VALIDATING |
| GB50_R100 | 538 | 0,011 | 0,000 | -0,036 | 31,2% | 48,9 | VALIDATING |
| GB40_R100 | 552 | 0,007 | 0,000 | -0,042 | 34,2% | 46,8 | VALIDATING |
| TP_R200 | 528 | -0,007 | 0,000 | -0,071 | 30,7% | 43,7 | VALIDATING |
| TP_R050 | 3 | -0,157 | 0,264 | -0,999 | 66,7% | 40,6 | INSUFFICIENT_DATA |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
