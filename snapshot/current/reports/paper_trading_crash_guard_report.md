# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T14:39:01+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **62**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **378.71 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 182 | 0 | 36064.28 |
| DOWN_20 | 182 | 0 | 72128.55 |
| DOWN_30 | 182 | 9 | 108316.61 |
| DOWN_40 | 182 | 55 | 137981.95 |
| UP_10 | 71 | 4 | 21467.09 |
| UP_20 | 71 | 4 | 42814.18 |
| UP_30 | 71 | 6 | 63875.81 |
| UP_40 | 71 | 36 | 77387.65 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
