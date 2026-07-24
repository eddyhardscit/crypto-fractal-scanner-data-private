# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T14:53:35+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **18**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-39.46 R**
- Profitto virtuale mancato: **77.89 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 114 | 0 | 12097.19 |
| DOWN_20 | 114 | 0 | 24194.38 |
| DOWN_30 | 114 | 11 | 36445.12 |
| DOWN_40 | 114 | 31 | 45893.99 |
| UP_10 | 66 | 0 | 18976.93 |
| UP_20 | 66 | 0 | 37953.87 |
| UP_30 | 66 | 0 | 56930.80 |
| UP_40 | 66 | 38 | 67513.45 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
