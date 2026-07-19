# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-19T21:09:54+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **0**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **0.00 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 39 | 0 | 7212.19 |
| DOWN_20 | 39 | 0 | 14424.38 |
| DOWN_30 | 39 | 0 | 21636.56 |
| DOWN_40 | 39 | 11 | 26820.85 |
| UP_10 | 29 | 0 | 5906.83 |
| UP_20 | 29 | 0 | 11813.66 |
| UP_30 | 29 | 1 | 17751.81 |
| UP_40 | 29 | 13 | 21855.93 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
