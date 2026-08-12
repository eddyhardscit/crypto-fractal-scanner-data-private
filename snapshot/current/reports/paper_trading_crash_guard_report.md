# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T17:39:10+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **72**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **378.71 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 150 | 0 | 22379.06 |
| DOWN_20 | 150 | 0 | 44758.12 |
| DOWN_30 | 150 | 0 | 67137.17 |
| DOWN_40 | 150 | 56 | 83578.54 |
| UP_10 | 78 | 0 | 22785.28 |
| UP_20 | 78 | 0 | 45570.56 |
| UP_30 | 78 | 0 | 68355.84 |
| UP_40 | 78 | 41 | 82211.49 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
