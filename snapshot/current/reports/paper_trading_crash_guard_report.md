# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-20T02:08:32+00:00

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
| DOWN_10 | 36 | 0 | 5737.04 |
| DOWN_20 | 36 | 1 | 11540.17 |
| DOWN_30 | 36 | 1 | 17227.64 |
| DOWN_40 | 36 | 11 | 21138.66 |
| UP_10 | 31 | 0 | 5124.52 |
| UP_20 | 31 | 0 | 10249.04 |
| UP_30 | 31 | 3 | 15415.39 |
| UP_40 | 31 | 18 | 19000.24 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
