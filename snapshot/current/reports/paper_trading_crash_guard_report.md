# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T14:38:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **16**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **14.15 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 129 | 2 | 16218.84 |
| DOWN_20 | 129 | 3 | 32377.68 |
| DOWN_30 | 129 | 3 | 48420.37 |
| DOWN_40 | 129 | 38 | 60964.84 |
| UP_10 | 55 | 0 | 14616.65 |
| UP_20 | 55 | 0 | 29233.30 |
| UP_30 | 55 | 0 | 43849.96 |
| UP_40 | 55 | 26 | 52280.32 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
