# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T07:08:41+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **110**
- Simulazioni bloccate attive: **111**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-17.73 R**
- Profitto virtuale mancato: **256.41 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 208 | 2 | 25063.13 |
| DOWN_20 | 208 | 3 | 50066.26 |
| DOWN_30 | 208 | 3 | 75047.82 |
| DOWN_40 | 208 | 78 | 93855.47 |
| UP_10 | 98 | 2 | 12963.74 |
| UP_20 | 98 | 3 | 25867.49 |
| UP_30 | 98 | 3 | 38654.49 |
| UP_40 | 98 | 53 | 46441.08 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
