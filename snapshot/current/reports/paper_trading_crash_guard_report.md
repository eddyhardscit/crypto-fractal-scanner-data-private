# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T06:25:01+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **72**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **326.19 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 131 | 0 | 26655.87 |
| DOWN_20 | 131 | 9 | 53805.59 |
| DOWN_30 | 131 | 11 | 80119.86 |
| DOWN_40 | 131 | 46 | 101085.88 |
| UP_10 | 110 | 0 | 23981.60 |
| UP_20 | 110 | 0 | 47963.20 |
| UP_30 | 110 | 0 | 71944.80 |
| UP_40 | 110 | 52 | 86609.15 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
