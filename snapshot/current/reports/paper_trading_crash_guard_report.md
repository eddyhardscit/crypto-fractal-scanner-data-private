# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T22:07:32+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **110**
- Simulazioni completate nel ciclo: **1**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **475.76 R**
- Profitto virtuale mancato: **506.35 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 215 | 0 | 31581.46 |
| DOWN_20 | 215 | 0 | 63162.92 |
| DOWN_30 | 215 | 0 | 94744.38 |
| DOWN_40 | 215 | 71 | 121079.91 |
| UP_10 | 160 | 0 | 32896.46 |
| UP_20 | 160 | 0 | 65792.91 |
| UP_30 | 160 | 0 | 98689.37 |
| UP_40 | 160 | 67 | 120082.41 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
