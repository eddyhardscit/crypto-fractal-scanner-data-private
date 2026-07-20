# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-20T06:08:30+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **3.03 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 38 | 0 | 6410.35 |
| DOWN_20 | 38 | 0 | 12820.71 |
| DOWN_30 | 38 | 1 | 19260.46 |
| DOWN_40 | 38 | 13 | 23667.00 |
| UP_10 | 31 | 0 | 6657.55 |
| UP_20 | 31 | 0 | 13315.11 |
| UP_30 | 31 | 0 | 19972.66 |
| UP_40 | 31 | 14 | 24658.10 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
