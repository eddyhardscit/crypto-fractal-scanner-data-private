# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T04:08:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **63**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **44.54 R**
- Profitto virtuale mancato: **163.76 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 306 | 0 | 36307.42 |
| DOWN_20 | 306 | 0 | 72614.85 |
| DOWN_30 | 306 | 0 | 108922.27 |
| DOWN_40 | 306 | 139 | 132944.61 |
| UP_10 | 98 | 0 | 13648.17 |
| UP_20 | 98 | 0 | 27296.33 |
| UP_30 | 98 | 0 | 40944.50 |
| UP_40 | 98 | 47 | 49314.05 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
