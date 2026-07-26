# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-26T05:38:49+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **30546**
- Valutazioni prodotte: **11544**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB50_R075 | 125 | 0,196 | 0,262 | 0,080 | 64,0% | 93,6 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 160 | 0,288 | 0,298 | 0,180 | 63,7% | 93,6 | ELIGIBLE_FOR_MUTATION |
| GB50_R100 | 121 | 0,157 | 0,249 | 0,031 | 63,6% | 93,6 | ELIGIBLE_FOR_MUTATION |
| GB40_R100 | 132 | 0,188 | 0,153 | 0,065 | 63,6% | 93,5 | ELIGIBLE_FOR_MUTATION |
| GB30_R100 | 159 | 0,185 | 0,219 | 0,072 | 60,4% | 90,3 | ELIGIBLE_FOR_MUTATION |
| GB20_R075 | 164 | 0,263 | 0,275 | 0,144 | 60,4% | 90,3 | ELIGIBLE_FOR_MUTATION |
| TP_R300 | 95 | 0,422 | 0,146 | 0,237 | 58,9% | 87,5 | VALIDATING |
| GB40_R075 | 136 | 0,204 | 0,298 | 0,079 | 56,6% | 86,6 | ELIGIBLE_FOR_MUTATION |
| TP_R250 | 95 | 0,227 | 0,063 | 0,078 | 56,8% | 85,0 | VALIDATING |
| GB30_R075 | 164 | 0,165 | 0,159 | 0,044 | 54,9% | 84,7 | VALIDATING |
| BE_A075 | 96 | 0,074 | 0,040 | -0,036 | 57,3% | 80,4 | VALIDATING |
| BE_A060 | 96 | 0,074 | 0,040 | -0,037 | 57,3% | 80,2 | VALIDATING |
| TP_R100 | 161 | 0,128 | 0,054 | 0,003 | 53,4% | 79,7 | VALIDATING |
| BE_R075 | 96 | 0,074 | 0,040 | -0,043 | 57,3% | 79,4 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 665 | 0,107 | 0,000 | 0,043 | 46,2% | 69,6 | VALIDATING |
| GB30_R050 | 665 | 0,067 | 0,000 | -0,001 | 44,7% | 69,5 | VALIDATING |
| TP_R200 | 470 | 0,092 | 0,000 | -0,001 | 46,4% | 65,8 | VALIDATING |
| GB20_R050 | 164 | 0,034 | 0,057 | -0,104 | 54,3% | 65,5 | VALIDATING |
| GB20_R100 | 651 | 0,079 | 0,000 | 0,024 | 37,5% | 65,5 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
