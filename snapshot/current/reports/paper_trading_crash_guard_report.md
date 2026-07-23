# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T03:23:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **17**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **14.14 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 118 | 0 | 18633.73 |
| DOWN_20 | 118 | 0 | 37267.47 |
| DOWN_30 | 118 | 0 | 55901.20 |
| DOWN_40 | 118 | 31 | 69991.71 |
| UP_10 | 39 | 0 | 6681.69 |
| UP_20 | 39 | 0 | 13363.37 |
| UP_30 | 39 | 0 | 20045.06 |
| UP_40 | 39 | 11 | 25525.86 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
