# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-29T00:53:39+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **14**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **221.05 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 75 | 0 | 12009.93 |
| DOWN_20 | 75 | 0 | 24019.86 |
| DOWN_30 | 75 | 0 | 36029.79 |
| DOWN_40 | 75 | 40 | 42574.50 |
| UP_10 | 176 | 0 | 19939.48 |
| UP_20 | 176 | 0 | 39878.97 |
| UP_30 | 176 | 0 | 59818.45 |
| UP_40 | 176 | 70 | 73133.25 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
