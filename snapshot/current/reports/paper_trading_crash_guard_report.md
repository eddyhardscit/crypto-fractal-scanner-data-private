# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T05:53:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **25**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-34.05 R**
- Profitto virtuale mancato: **67.43 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 120 | 0 | 13927.75 |
| DOWN_20 | 120 | 0 | 27855.50 |
| DOWN_30 | 120 | 2 | 41817.34 |
| DOWN_40 | 120 | 38 | 52627.64 |
| UP_10 | 64 | 0 | 18403.79 |
| UP_20 | 64 | 0 | 36807.58 |
| UP_30 | 64 | 0 | 55211.37 |
| UP_40 | 64 | 36 | 65562.11 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
