# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T03:06:27+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **67**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **519.19 R**
- Profitto virtuale mancato: **506.35 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 192 | 0 | 27885.19 |
| DOWN_20 | 192 | 0 | 55770.39 |
| DOWN_30 | 192 | 1 | 83668.77 |
| DOWN_40 | 192 | 56 | 107546.74 |
| UP_10 | 167 | 0 | 33111.23 |
| UP_20 | 167 | 0 | 66222.47 |
| UP_30 | 167 | 0 | 99333.70 |
| UP_40 | 167 | 72 | 120852.44 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
