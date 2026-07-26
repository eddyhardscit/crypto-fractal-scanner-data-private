# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-26T06:38:53+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **31830**
- Valutazioni prodotte: **11760**
- Candidature al Blocco 5: **1**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| GB50_R100 | 148 | 0,127 | 0,189 | 0,017 | 61,5% | 87,6 | VALIDATING |
| TP_R250 | 110 | 0,186 | 0,120 | 0,034 | 57,3% | 86,1 | ROBUST |
| GB20_R100 | 201 | 0,223 | 0,148 | 0,122 | 59,7% | 85,8 | VALIDATING |
| TP_R300 | 101 | 0,322 | 0,054 | 0,122 | 55,4% | 85,0 | ROBUST |
| GB50_R075 | 158 | 0,105 | 0,262 | -0,012 | 60,1% | 84,4 | VALIDATING |
| GB20_R075 | 205 | 0,171 | 0,076 | 0,062 | 57,1% | 83,2 | VALIDATING |
| GB40_R100 | 171 | 0,110 | 0,095 | 0,005 | 56,7% | 83,0 | VALIDATING |
| GB30_R100 | 201 | 0,123 | 0,143 | 0,025 | 55,2% | 81,4 | VALIDATING |
| TP_R100 | 201 | 0,086 | 0,054 | -0,019 | 52,7% | 76,2 | VALIDATING |
| GB40_R075 | 175 | 0,099 | 0,093 | -0,014 | 52,0% | 76,1 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB30_R075 | 205 | 0,090 | 0,049 | -0,013 | 50,7% | 71,0 | VALIDATING |
| GB20_R050 | 665 | 0,107 | 0,000 | 0,043 | 46,2% | 69,6 | VALIDATING |
| GB30_R050 | 665 | 0,067 | 0,000 | -0,001 | 44,7% | 69,5 | VALIDATING |
| TP_R200 | 471 | 0,093 | 0,000 | 0,004 | 46,5% | 66,0 | VALIDATING |
| GB20_R100 | 651 | 0,079 | 0,000 | 0,024 | 37,5% | 65,5 | VALIDATING |
| TP_R150 | 646 | 0,051 | 0,000 | -0,002 | 28,0% | 65,1 | VALIDATING |
| TP_R100 | 651 | 0,048 | 0,000 | -0,009 | 35,3% | 64,1 | VALIDATING |
| TIME_4H | 7 | 0,313 | 0,534 | 0,084 | 57,1% | 63,4 | INSUFFICIENT_DATA |
| BE_A075 | 103 | 0,033 | 0,010 | -0,071 | 53,4% | 61,3 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
