# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T16:24:59+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **162**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **145.47 R**
- Profitto virtuale mancato: **417.45 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 112 | 4 | 11296.70 |
| DOWN_20 | 112 | 6 | 22473.41 |
| DOWN_30 | 112 | 6 | 33421.61 |
| DOWN_40 | 112 | 43 | 41951.75 |
| UP_10 | 163 | 0 | 47330.74 |
| UP_20 | 163 | 0 | 94661.48 |
| UP_30 | 163 | 0 | 141992.21 |
| UP_40 | 163 | 80 | 170516.56 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
