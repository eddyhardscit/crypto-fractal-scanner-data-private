# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T08:23:36+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **17**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-86.30 R**
- Profitto virtuale mancato: **142.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 151 | 0 | 13953.49 |
| DOWN_20 | 151 | 0 | 27906.98 |
| DOWN_30 | 151 | 0 | 41860.47 |
| DOWN_40 | 151 | 55 | 53007.02 |
| UP_10 | 74 | 0 | 22834.98 |
| UP_20 | 74 | 0 | 45669.96 |
| UP_30 | 74 | 0 | 68504.94 |
| UP_40 | 74 | 48 | 79689.95 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
