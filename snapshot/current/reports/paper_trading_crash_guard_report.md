# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T23:08:35+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **37**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-21.28 R**
- Profitto virtuale mancato: **77.89 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 112 | 0 | 11799.59 |
| DOWN_20 | 112 | 0 | 23599.18 |
| DOWN_30 | 112 | 0 | 35398.78 |
| DOWN_40 | 112 | 44 | 44927.99 |
| UP_10 | 74 | 0 | 20899.38 |
| UP_20 | 74 | 0 | 41798.77 |
| UP_30 | 74 | 0 | 62698.15 |
| UP_40 | 74 | 48 | 73200.24 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
