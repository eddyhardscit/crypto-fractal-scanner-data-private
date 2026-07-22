# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-22T15:23:35+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **14.14 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 115 | 0 | 19768.42 |
| DOWN_20 | 115 | 0 | 39536.83 |
| DOWN_30 | 115 | 0 | 59305.25 |
| DOWN_40 | 115 | 32 | 74034.49 |
| UP_10 | 61 | 0 | 13173.10 |
| UP_20 | 61 | 0 | 26346.20 |
| UP_30 | 61 | 0 | 39519.30 |
| UP_40 | 61 | 24 | 48933.63 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
