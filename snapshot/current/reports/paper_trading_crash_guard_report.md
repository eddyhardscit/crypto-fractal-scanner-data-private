# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T15:38:42+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **143.26 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 64 | 0 | 6610.40 |
| DOWN_20 | 64 | 0 | 13220.80 |
| DOWN_30 | 64 | 7 | 19915.14 |
| DOWN_40 | 64 | 13 | 25341.60 |
| UP_10 | 235 | 0 | 27553.06 |
| UP_20 | 235 | 0 | 55106.11 |
| UP_30 | 235 | 11 | 83384.74 |
| UP_40 | 235 | 95 | 100991.64 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
