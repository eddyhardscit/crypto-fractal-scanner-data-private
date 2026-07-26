# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T05:38:36+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **71**
- Simulazioni completate nel ciclo: **1**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **23.59 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 285 | 0 | 22199.31 |
| DOWN_20 | 285 | 0 | 44398.61 |
| DOWN_30 | 285 | 5 | 66684.39 |
| DOWN_40 | 285 | 98 | 83542.80 |
| UP_10 | 81 | 0 | 12876.99 |
| UP_20 | 81 | 0 | 25753.98 |
| UP_30 | 81 | 0 | 38630.97 |
| UP_40 | 81 | 30 | 45953.14 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
