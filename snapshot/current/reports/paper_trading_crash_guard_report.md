# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T01:53:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **3**
- Simulazioni completate nel ciclo: **2**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-17.38 R**
- Profitto virtuale mancato: **47.73 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 113 | 0 | 13748.46 |
| DOWN_20 | 113 | 0 | 27496.93 |
| DOWN_30 | 113 | 2 | 41274.26 |
| DOWN_40 | 113 | 27 | 52094.47 |
| UP_10 | 67 | 0 | 18957.57 |
| UP_20 | 67 | 0 | 37915.15 |
| UP_30 | 67 | 0 | 56872.72 |
| UP_40 | 67 | 39 | 66729.18 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
