# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T11:38:41+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **3456**
- Valutazioni prodotte: **2605**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_6H | 133 | 0,073 | 0,036 | -0,023 | 60,2% | 86,3 | VALIDATING |
| GB20_R050 | 135 | 0,289 | 0,060 | 0,151 | 52,6% | 82,6 | VALIDATING |
| TP_R050 | 135 | 0,208 | 0,060 | 0,068 | 52,6% | 82,5 | VALIDATING |
| GB30_R050 | 135 | 0,263 | 0,060 | 0,134 | 51,9% | 81,9 | VALIDATING |
| GB40_R050 | 135 | 0,220 | 0,060 | 0,080 | 51,9% | 81,8 | VALIDATING |
| GB50_R050 | 135 | 0,176 | 0,044 | 0,050 | 51,9% | 81,2 | VALIDATING |
| GB20_R100 | 134 | 0,187 | 0,017 | 0,077 | 50,0% | 75,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| TP_R200 | 124 | 0,139 | 0,000 | 0,027 | 43,5% | 73,0 | VALIDATING |
| TP_R100 | 134 | 0,163 | 0,000 | 0,052 | 48,5% | 69,5 | VALIDATING |
| GB30_R100 | 134 | 0,155 | 0,000 | 0,051 | 48,5% | 69,4 | VALIDATING |
| GB40_R100 | 134 | 0,116 | 0,000 | 0,021 | 49,3% | 69,3 | VALIDATING |
| GB50_R100 | 123 | 0,125 | 0,000 | 0,043 | 49,6% | 69,2 | VALIDATING |
| TIME_12H | 124 | 0,154 | 0,000 | 0,049 | 49,2% | 68,3 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R150 | 124 | 0,034 | 0,000 | -0,060 | 38,7% | 56,5 | VALIDATING |
| ATR15_R100 | 119 | -0,006 | 0,000 | -0,084 | 41,2% | 41,3 | VALIDATING |
| ATR20_R100 | 119 | -0,042 | 0,000 | -0,148 | 40,3% | 39,2 | VALIDATING |
| BE_R050 | 132 | -0,119 | 0,000 | -0,287 | 38,6% | 34,6 | VALIDATING |
| TIME_24H | 112 | -0,081 | 0,000 | -0,286 | 39,3% | 34,2 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
