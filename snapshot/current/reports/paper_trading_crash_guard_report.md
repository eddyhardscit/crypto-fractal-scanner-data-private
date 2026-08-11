# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T20:24:55+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **195**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **156.51 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 101 | 0 | 11668.03 |
| DOWN_20 | 101 | 0 | 23336.05 |
| DOWN_30 | 101 | 2 | 34775.58 |
| DOWN_40 | 101 | 22 | 44131.79 |
| UP_10 | 165 | 0 | 40925.24 |
| UP_20 | 165 | 0 | 81850.48 |
| UP_30 | 165 | 11 | 122931.90 |
| UP_40 | 165 | 86 | 147846.49 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
