# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-22T10:08:34+00:00

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
| DOWN_10 | 95 | 0 | 15739.51 |
| DOWN_20 | 95 | 0 | 31479.02 |
| DOWN_30 | 95 | 1 | 47234.77 |
| DOWN_40 | 95 | 23 | 59935.07 |
| UP_10 | 53 | 0 | 11003.59 |
| UP_20 | 53 | 0 | 22007.17 |
| UP_30 | 53 | 0 | 33010.76 |
| UP_40 | 53 | 23 | 40365.16 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
