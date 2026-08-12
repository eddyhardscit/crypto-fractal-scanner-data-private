# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T15:39:10+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **62**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **378.71 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 124 | 0 | 21264.88 |
| DOWN_20 | 124 | 0 | 42529.76 |
| DOWN_30 | 124 | 0 | 63794.64 |
| DOWN_40 | 124 | 49 | 79344.76 |
| UP_10 | 74 | 0 | 22784.62 |
| UP_20 | 74 | 0 | 45569.24 |
| UP_30 | 74 | 0 | 68353.86 |
| UP_40 | 74 | 37 | 82465.08 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
