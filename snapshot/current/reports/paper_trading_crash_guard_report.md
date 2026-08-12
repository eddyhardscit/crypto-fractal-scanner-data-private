# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T07:39:09+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **60**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **349.42 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 93 | 0 | 16822.13 |
| DOWN_20 | 93 | 0 | 33644.25 |
| DOWN_30 | 93 | 2 | 50495.16 |
| DOWN_40 | 93 | 29 | 63814.24 |
| UP_10 | 90 | 0 | 28022.61 |
| UP_20 | 90 | 0 | 56045.22 |
| UP_30 | 90 | 0 | 84067.83 |
| UP_40 | 90 | 40 | 102193.55 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
