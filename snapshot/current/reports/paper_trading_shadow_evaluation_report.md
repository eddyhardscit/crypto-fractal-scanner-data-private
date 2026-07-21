# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-21T17:53:42+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **4810**
- Valutazioni prodotte: **2935**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 205 | 0,221 | 0,000 | 0,109 | 46,3% | 73,9 | VALIDATING |
| GB30_R100 | 200 | 0,123 | 0,000 | 0,043 | 40,0% | 73,5 | VALIDATING |
| GB50_R100 | 185 | 0,120 | 0,000 | 0,055 | 43,2% | 73,3 | VALIDATING |
| GB20_R100 | 201 | 0,150 | 0,000 | 0,062 | 41,3% | 73,2 | VALIDATING |
| TP_R200 | 165 | 0,120 | 0,000 | 0,039 | 35,2% | 73,2 | VALIDATING |
| TIME_12H | 194 | 0,078 | 0,000 | 0,007 | 37,6% | 72,4 | VALIDATING |
| TIME_6H | 204 | 0,040 | 0,036 | -0,059 | 55,9% | 71,1 | VALIDATING |
| GB30_R050 | 205 | 0,191 | 0,000 | 0,073 | 46,3% | 70,2 | VALIDATING |
| TP_R050 | 211 | 0,131 | 0,000 | 0,022 | 45,0% | 70,1 | VALIDATING |
| GB40_R050 | 205 | 0,148 | 0,000 | 0,032 | 45,9% | 70,1 | VALIDATING |
| GB50_R050 | 205 | 0,107 | 0,000 | 0,003 | 45,9% | 69,7 | VALIDATING |
| GB40_R100 | 200 | 0,088 | 0,000 | 0,009 | 42,5% | 69,3 | VALIDATING |
| TP_R100 | 208 | 0,115 | 0,000 | 0,030 | 39,9% | 65,6 | VALIDATING |
| TP_R150 | 192 | 0,088 | 0,000 | 0,008 | 31,8% | 65,0 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| ATR15_R100 | 175 | -0,019 | 0,000 | -0,077 | 31,4% | 38,2 | VALIDATING |
| ATR20_R100 | 174 | -0,062 | 0,000 | -0,139 | 29,3% | 35,6 | VALIDATING |
| BE_R050 | 184 | -0,054 | 0,000 | -0,180 | 35,3% | 35,2 | VALIDATING |
| TIME_24H | 160 | -0,034 | 0,000 | -0,167 | 33,1% | 34,8 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
