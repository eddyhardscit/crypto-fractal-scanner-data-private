# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-30T20:08:39+00:00

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
| DOWN_10 | 47 | 0 | 3572.61 |
| DOWN_20 | 47 | 0 | 7145.22 |
| DOWN_30 | 47 | 0 | 10717.82 |
| DOWN_40 | 47 | 20 | 13691.26 |
| UP_10 | 65 | 0 | 3668.85 |
| UP_20 | 65 | 0 | 7337.70 |
| UP_30 | 65 | 0 | 11006.54 |
| UP_40 | 65 | 16 | 14032.24 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
