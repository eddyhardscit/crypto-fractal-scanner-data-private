# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T19:39:02+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **62**
- Simulazioni completate nel ciclo: **10**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **388.81 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 155 | 0 | 20642.82 |
| DOWN_20 | 155 | 0 | 41285.64 |
| DOWN_30 | 155 | 0 | 61928.46 |
| DOWN_40 | 155 | 54 | 77839.61 |
| UP_10 | 83 | 0 | 23514.24 |
| UP_20 | 83 | 0 | 47028.48 |
| UP_30 | 83 | 4 | 70600.08 |
| UP_40 | 83 | 43 | 85071.37 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
