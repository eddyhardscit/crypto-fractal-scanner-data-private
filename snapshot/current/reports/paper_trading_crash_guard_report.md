# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-22T20:23:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **6**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **14.14 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 116 | 0 | 18387.92 |
| DOWN_20 | 116 | 0 | 36775.84 |
| DOWN_30 | 116 | 1 | 55183.08 |
| DOWN_40 | 116 | 31 | 68998.37 |
| UP_10 | 38 | 0 | 6602.70 |
| UP_20 | 38 | 0 | 13205.40 |
| UP_30 | 38 | 0 | 19808.10 |
| UP_40 | 38 | 12 | 24964.73 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
