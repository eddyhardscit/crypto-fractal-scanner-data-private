# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T00:39:09+00:00

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
| DOWN_10 | 262 | 0 | 23014.56 |
| DOWN_20 | 262 | 0 | 46029.12 |
| DOWN_30 | 262 | 36 | 69605.61 |
| DOWN_40 | 262 | 107 | 86044.65 |
| UP_10 | 85 | 0 | 15603.26 |
| UP_20 | 85 | 0 | 31206.52 |
| UP_30 | 85 | 2 | 46842.50 |
| UP_40 | 85 | 48 | 56285.89 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
