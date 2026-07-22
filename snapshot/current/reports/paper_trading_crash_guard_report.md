# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-22T07:08:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **8**
- Simulazioni bloccate attive: **9**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **6.06 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 77 | 0 | 17174.32 |
| DOWN_20 | 77 | 0 | 34348.64 |
| DOWN_30 | 77 | 0 | 51522.96 |
| DOWN_40 | 77 | 18 | 65800.79 |
| UP_10 | 48 | 0 | 9301.31 |
| UP_20 | 48 | 0 | 18602.62 |
| UP_30 | 48 | 2 | 27931.00 |
| UP_40 | 48 | 28 | 33070.83 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
