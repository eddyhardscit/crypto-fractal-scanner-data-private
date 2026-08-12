# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T09:39:07+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **78**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **349.42 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 110 | 0 | 17111.74 |
| DOWN_20 | 110 | 0 | 34223.47 |
| DOWN_30 | 110 | 2 | 51363.99 |
| DOWN_40 | 110 | 34 | 64832.24 |
| UP_10 | 97 | 0 | 28528.59 |
| UP_20 | 97 | 0 | 57057.18 |
| UP_30 | 97 | 1 | 85667.74 |
| UP_40 | 97 | 46 | 104454.57 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
