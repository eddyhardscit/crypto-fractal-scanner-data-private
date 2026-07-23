# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T17:38:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **13**
- Simulazioni completate nel ciclo: **2**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **4.26 R**
- Profitto virtuale mancato: **11.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 124 | 0 | 15147.17 |
| DOWN_20 | 124 | 0 | 30294.33 |
| DOWN_30 | 124 | 3 | 45500.42 |
| DOWN_40 | 124 | 38 | 57156.08 |
| UP_10 | 57 | 0 | 15026.76 |
| UP_20 | 57 | 0 | 30053.51 |
| UP_30 | 57 | 0 | 45080.27 |
| UP_40 | 57 | 29 | 53564.22 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
