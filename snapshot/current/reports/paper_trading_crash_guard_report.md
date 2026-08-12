# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T18:39:03+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **72**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **378.71 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 154 | 0 | 21070.37 |
| DOWN_20 | 154 | 0 | 42140.73 |
| DOWN_30 | 154 | 0 | 63211.10 |
| DOWN_40 | 154 | 53 | 79266.46 |
| UP_10 | 79 | 0 | 22829.01 |
| UP_20 | 79 | 0 | 45658.02 |
| UP_30 | 79 | 4 | 68544.40 |
| UP_40 | 79 | 42 | 82357.25 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
