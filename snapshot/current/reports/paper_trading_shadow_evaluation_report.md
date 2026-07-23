# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-23T01:23:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **10479**
- Valutazioni prodotte: **3287**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 474 | 0,194 | 0,000 | 0,118 | 47,7% | 73,8 | VALIDATING |
| TP_R050 | 474 | 0,120 | 0,000 | 0,047 | 46,0% | 73,8 | VALIDATING |
| GB30_R050 | 474 | 0,160 | 0,000 | 0,093 | 46,4% | 73,7 | VALIDATING |
| GB40_R050 | 474 | 0,121 | 0,000 | 0,050 | 46,0% | 73,7 | VALIDATING |
| GB20_R100 | 467 | 0,106 | 0,000 | 0,055 | 37,0% | 73,5 | VALIDATING |
| GB30_R100 | 466 | 0,082 | 0,000 | 0,033 | 36,7% | 73,5 | VALIDATING |
| TIME_6H | 473 | 0,031 | 0,043 | -0,043 | 53,9% | 72,5 | VALIDATING |
| TP_R150 | 442 | 0,047 | 0,000 | -0,009 | 27,1% | 71,7 | VALIDATING |
| GB50_R050 | 474 | 0,078 | 0,000 | 0,011 | 45,4% | 69,9 | VALIDATING |
| TP_R100 | 467 | 0,075 | 0,000 | 0,018 | 35,3% | 69,8 | VALIDATING |
| GB40_R100 | 466 | 0,060 | 0,000 | 0,010 | 36,7% | 69,6 | VALIDATING |
| GB50_R100 | 466 | 0,043 | 0,000 | -0,002 | 34,3% | 68,4 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TIME_12H | 472 | 0,040 | 0,000 | -0,033 | 44,1% | 58,3 | VALIDATING |
| TP_R200 | 417 | -0,024 | 0,000 | -0,094 | 30,2% | 39,9 | VALIDATING |
| TIME_24H | 448 | -0,069 | 0,000 | -0,167 | 28,6% | 34,7 | VALIDATING |
| BE_R050 | 431 | -0,085 | 0,000 | -0,161 | 29,0% | 32,1 | UNDERPERFORMING |
| ATR15_R100 | 466 | -0,054 | 0,000 | -0,101 | 27,9% | 31,1 | UNDERPERFORMING |
| ATR30_R100 | 445 | -0,114 | 0,000 | -0,186 | 22,9% | 31,0 | UNDERPERFORMING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
