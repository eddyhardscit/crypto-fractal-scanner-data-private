# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-31T22:38:39+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **196.28 R**
- Profitto virtuale mancato: **312.09 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 16 | 4 | 898.93 |
| DOWN_20 | 16 | 6 | 1677.87 |
| DOWN_30 | 16 | 6 | 2337.09 |
| DOWN_40 | 16 | 10 | 2913.23 |
| UP_10 | 34 | 0 | 1326.54 |
| UP_20 | 34 | 0 | 2653.08 |
| UP_30 | 34 | 0 | 3979.63 |
| UP_40 | 34 | 8 | 4854.60 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
