# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T18:24:31+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **224**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **127.21 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 106 | 4 | 11831.07 |
| DOWN_20 | 106 | 6 | 23542.14 |
| DOWN_30 | 106 | 6 | 35024.71 |
| DOWN_40 | 106 | 27 | 44396.43 |
| UP_10 | 152 | 0 | 39731.60 |
| UP_20 | 152 | 0 | 79463.21 |
| UP_30 | 152 | 0 | 119194.81 |
| UP_40 | 152 | 72 | 143840.04 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
