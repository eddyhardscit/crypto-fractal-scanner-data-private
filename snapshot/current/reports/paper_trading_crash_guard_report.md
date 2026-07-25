# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T17:23:39+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **69**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-41.14 R**
- Profitto virtuale mancato: **144.40 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 187 | 0 | 17725.12 |
| DOWN_20 | 187 | 0 | 35450.24 |
| DOWN_30 | 187 | 0 | 53175.36 |
| DOWN_40 | 187 | 47 | 68249.56 |
| UP_10 | 112 | 0 | 25588.31 |
| UP_20 | 112 | 0 | 51176.62 |
| UP_30 | 112 | 0 | 76764.93 |
| UP_40 | 112 | 60 | 91336.96 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
