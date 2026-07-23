# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T19:38:35+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **25**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **9.33 R**
- Profitto virtuale mancato: **11.92 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 125 | 0 | 15380.94 |
| DOWN_20 | 125 | 0 | 30761.88 |
| DOWN_30 | 125 | 0 | 46142.82 |
| DOWN_40 | 125 | 38 | 57957.08 |
| UP_10 | 62 | 0 | 16474.99 |
| UP_20 | 62 | 0 | 32949.97 |
| UP_30 | 62 | 0 | 49424.96 |
| UP_40 | 62 | 35 | 58354.67 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
