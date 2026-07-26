# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T02:38:36+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **67**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **22.58 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 264 | 0 | 21260.62 |
| DOWN_20 | 264 | 0 | 42521.25 |
| DOWN_30 | 264 | 0 | 63781.87 |
| DOWN_40 | 264 | 100 | 80311.56 |
| UP_10 | 89 | 0 | 15326.03 |
| UP_20 | 89 | 0 | 30652.05 |
| UP_30 | 89 | 0 | 45978.08 |
| UP_40 | 89 | 32 | 55288.89 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
