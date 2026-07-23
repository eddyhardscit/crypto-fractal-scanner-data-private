# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-23T20:38:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **6**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **0.39 R**
- Profitto virtuale mancato: **20.86 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 121 | 0 | 14012.17 |
| DOWN_20 | 121 | 0 | 28024.33 |
| DOWN_30 | 121 | 2 | 42071.44 |
| DOWN_40 | 121 | 36 | 52992.42 |
| UP_10 | 68 | 0 | 17421.72 |
| UP_20 | 68 | 0 | 34843.43 |
| UP_30 | 68 | 0 | 52265.15 |
| UP_40 | 68 | 38 | 61635.67 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
