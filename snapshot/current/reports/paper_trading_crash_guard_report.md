# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T10:53:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **71**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **25.61 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 260 | 0 | 22004.49 |
| DOWN_20 | 260 | 0 | 44008.98 |
| DOWN_30 | 260 | 1 | 66014.46 |
| DOWN_40 | 260 | 107 | 83340.78 |
| UP_10 | 81 | 0 | 12676.66 |
| UP_20 | 81 | 0 | 25353.31 |
| UP_30 | 81 | 0 | 38029.97 |
| UP_40 | 81 | 41 | 45170.35 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
