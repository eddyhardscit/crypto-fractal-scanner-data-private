# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-21T05:38:32+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **5.05 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 99 | 0 | 24676.07 |
| DOWN_20 | 99 | 0 | 49352.14 |
| DOWN_30 | 99 | 1 | 74042.96 |
| DOWN_40 | 99 | 41 | 89470.68 |
| UP_10 | 28 | 0 | 3997.83 |
| UP_20 | 28 | 0 | 7995.66 |
| UP_30 | 28 | 0 | 11993.49 |
| UP_40 | 28 | 9 | 15568.93 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
