# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T09:38:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **36**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **154.60 R**
- Profitto virtuale mancato: **269.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 79 | 0 | 8679.36 |
| DOWN_20 | 79 | 0 | 17358.71 |
| DOWN_30 | 79 | 5 | 26107.69 |
| DOWN_40 | 79 | 13 | 33336.24 |
| UP_10 | 271 | 0 | 33381.66 |
| UP_20 | 271 | 0 | 66763.32 |
| UP_30 | 271 | 5 | 100216.44 |
| UP_40 | 271 | 143 | 119368.64 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
