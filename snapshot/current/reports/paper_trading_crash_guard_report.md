# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T17:25:27+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **1**
- Simulazioni bloccate attive: **195**
- Simulazioni completate nel ciclo: **4**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **149.51 R**
- Profitto virtuale mancato: **417.45 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 116 | 4 | 12444.02 |
| DOWN_20 | 116 | 6 | 24768.03 |
| DOWN_30 | 116 | 6 | 36863.55 |
| DOWN_40 | 116 | 22 | 46260.14 |
| UP_10 | 165 | 0 | 43593.39 |
| UP_20 | 165 | 0 | 87186.79 |
| UP_30 | 165 | 0 | 130780.18 |
| UP_40 | 165 | 82 | 157210.94 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
