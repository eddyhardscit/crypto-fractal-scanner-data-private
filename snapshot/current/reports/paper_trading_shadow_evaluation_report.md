# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T05:38:39+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **2567**
- Valutazioni prodotte: **2246**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 92 | 0,280 | 0,000 | 0,126 | 48,9% | 68,4 | VALIDATING |
| GB30_R050 | 92 | 0,246 | 0,000 | 0,096 | 47,8% | 68,4 | VALIDATING |
| GB40_R050 | 92 | 0,205 | 0,000 | 0,047 | 47,8% | 68,3 | VALIDATING |
| TP_R050 | 92 | 0,197 | 0,000 | 0,023 | 48,9% | 68,3 | VALIDATING |
| GB50_R050 | 92 | 0,205 | 0,000 | 0,055 | 47,8% | 68,3 | VALIDATING |
| GB20_R100 | 91 | 0,146 | 0,000 | 0,024 | 42,9% | 68,1 | VALIDATING |
| TIME_12H | 92 | 0,149 | 0,000 | 0,024 | 44,6% | 66,6 | VALIDATING |
| TIME_6H | 92 | 0,058 | 0,003 | -0,030 | 51,1% | 65,3 | VALIDATING |
| TP_R100 | 91 | 0,120 | 0,000 | 0,000 | 42,9% | 64,3 | VALIDATING |
| GB30_R100 | 89 | 0,082 | 0,000 | -0,029 | 41,6% | 59,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| GB50_R100 | 87 | 0,040 | 0,000 | -0,057 | 40,2% | 56,8 | VALIDATING |
| TP_R200 | 79 | 0,098 | 0,000 | -0,025 | 35,4% | 56,7 | VALIDATING |
| BE_R050 | 85 | 0,078 | 0,000 | -0,071 | 38,8% | 56,4 | VALIDATING |
| TP_R150 | 83 | 0,038 | 0,000 | -0,079 | 31,3% | 47,5 | VALIDATING |
| GB40_R100 | 88 | 0,031 | 0,000 | -0,086 | 40,9% | 45,9 | VALIDATING |
| TIME_24H | 69 | 0,019 | 0,000 | -0,140 | 31,9% | 33,9 | VALIDATING |
| TP_R150 | 6 | 0,056 | 0,000 | -0,433 | 16,7% | 28,7 | INSUFFICIENT_DATA |
| ATR15_R100 | 85 | -0,105 | 0,000 | -0,200 | 35,3% | 26,7 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
