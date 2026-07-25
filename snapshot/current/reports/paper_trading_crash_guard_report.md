# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T21:38:52+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **69**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-41.14 R**
- Profitto virtuale mancato: **144.40 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 257 | 0 | 22612.74 |
| DOWN_20 | 257 | 0 | 45225.49 |
| DOWN_30 | 257 | 34 | 68367.73 |
| DOWN_40 | 257 | 102 | 84706.20 |
| UP_10 | 101 | 4 | 19274.19 |
| UP_20 | 101 | 6 | 38428.37 |
| UP_30 | 101 | 16 | 57310.06 |
| UP_40 | 101 | 61 | 68471.44 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
