# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T15:25:56+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **32**
- Simulazioni bloccate attive: **81**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **145.47 R**
- Profitto virtuale mancato: **417.45 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 105 | 0 | 10561.11 |
| DOWN_20 | 105 | 0 | 21122.23 |
| DOWN_30 | 105 | 0 | 31683.34 |
| DOWN_40 | 105 | 37 | 39826.39 |
| UP_10 | 141 | 0 | 42260.86 |
| UP_20 | 141 | 0 | 84521.72 |
| UP_30 | 141 | 0 | 126782.57 |
| UP_40 | 141 | 68 | 153126.61 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
