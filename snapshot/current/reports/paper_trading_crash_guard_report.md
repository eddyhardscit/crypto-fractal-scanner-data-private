# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-01T21:08:42+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **196.28 R**
- Profitto virtuale mancato: **312.09 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 15 | 6 | 1023.88 |
| DOWN_20 | 15 | 9 | 1867.76 |
| DOWN_30 | 15 | 9 | 2141.42 |
| DOWN_40 | 15 | 13 | 2332.00 |
| UP_10 | 29 | 0 | 1183.14 |
| UP_20 | 29 | 0 | 2366.28 |
| UP_30 | 29 | 0 | 3549.41 |
| UP_40 | 29 | 6 | 4280.98 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
