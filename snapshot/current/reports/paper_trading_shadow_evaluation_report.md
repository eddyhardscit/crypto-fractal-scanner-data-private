# Blocco 4 — Valutazione statistica Shadow

Generato: 2026-07-25T00:08:50+00:00

> Modulo esclusivamente valutativo. Non modifica strategie, uscite, posizioni o capitale. Le candidature vengono consegnate al futuro Blocco 5, senza applicazione automatica.

## Stato

- Risultati Block 3 disponibili: **18506**
- Valutazioni prodotte: **5322**
- Candidature al Blocco 5: **0**
- Mutazioni create automaticamente: **0**

## Classifica complessiva

| Scenario | Campione pieno | Δ medio (R) | Mediana (R) | CI bootstrap basso | Migliora | Score | Stato |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | --- |
| TP_R100 | 232 | 0,227 | 0,322 | 0,112 | 67,7% | 95,0 | ELIGIBLE_FOR_MUTATION |
| GB30_R100 | 232 | 0,205 | 0,322 | 0,090 | 69,4% | 94,8 | ELIGIBLE_FOR_MUTATION |
| GB20_R100 | 232 | 0,236 | 0,322 | 0,121 | 68,1% | 91,2 | VALIDATING |
| GB20_R050 | 234 | 0,205 | 0,294 | 0,105 | 67,5% | 91,2 | VALIDATING |
| GB40_R100 | 230 | 0,152 | 0,281 | 0,044 | 67,8% | 91,2 | VALIDATING |
| GB30_R050 | 234 | 0,150 | 0,262 | 0,048 | 67,5% | 91,2 | VALIDATING |
| GB50_R100 | 226 | 0,099 | 0,286 | -0,007 | 67,7% | 90,0 | VALIDATING |
| GB40_R050 | 234 | 0,093 | 0,219 | -0,010 | 65,4% | 89,5 | VALIDATING |
| GB50_R050 | 232 | 0,082 | 0,169 | -0,014 | 65,9% | 88,8 | VALIDATING |
| TP_R050 | 234 | 0,061 | 0,264 | -0,034 | 66,2% | 85,0 | VALIDATING |
| TP_R150 | 210 | 0,141 | 0,078 | 0,009 | 54,3% | 84,0 | VALIDATING |
| TIME_24H | 6 | 0,997 | 1,104 | 0,180 | 66,7% | 74,1 | INSUFFICIENT_DATA |
| GB20_R050 | 655 | 0,092 | 0,000 | 0,031 | 45,8% | 70,0 | VALIDATING |
| TP_R150 | 632 | 0,065 | 0,000 | 0,013 | 28,2% | 69,8 | VALIDATING |
| GB20_R100 | 641 | 0,063 | 0,000 | 0,014 | 37,1% | 69,7 | VALIDATING |
| GB30_R050 | 655 | 0,052 | 0,000 | -0,014 | 44,3% | 67,9 | VALIDATING |
| TP_R200 | 202 | 0,054 | 0,104 | -0,113 | 55,9% | 66,8 | VALIDATING |
| TP_R200 | 622 | 0,051 | 0,000 | -0,014 | 35,2% | 63,8 | VALIDATING |
| TP_R200 | 6 | 0,472 | 0,250 | -0,017 | 50,0% | 58,7 | INSUFFICIENT_DATA |
| TP_R100 | 641 | 0,031 | 0,000 | -0,022 | 34,9% | 58,0 | VALIDATING |

## Stati di evidenza

- **INSUFFICIENT_DATA**: meno di 30 trade completi.
- **EARLY_SIGNAL**: da 30 a 49 trade completi.
- **VALIDATING**: campione maggiore, ma robustezza non ancora dimostrata.
- **ROBUST**: test di effetto, stabilità, qualità e outlier superati.
- **ELIGIBLE_FOR_MUTATION**: evidenza sufficiente per proporre una variante al Blocco 5.
- **UNDERPERFORMING**: intervallo statistico stabilmente negativo.

## Protezioni statistiche

Sono utilizzati solo trade osservati integralmente dall'entrata. Il controllo comprende media e mediana normalizzate per rischio, media tagliata, bootstrap deterministico, quattro segmenti temporali, concentrazione dei migliori outlier, ambiguità intrabar e gap di candele.
