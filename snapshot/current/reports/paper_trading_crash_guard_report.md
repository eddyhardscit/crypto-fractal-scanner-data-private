# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T14:25:09+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **4**
- Simulazioni bloccate attive: **4**
- Simulazioni completate nel ciclo: **29**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **145.47 R**
- Profitto virtuale mancato: **417.45 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 201 | 0 | 28894.22 |
| DOWN_20 | 201 | 0 | 57788.44 |
| DOWN_30 | 201 | 0 | 86682.66 |
| DOWN_40 | 201 | 71 | 108559.56 |
| UP_10 | 69 | 0 | 16506.46 |
| UP_20 | 69 | 0 | 33012.91 |
| UP_30 | 69 | 0 | 49519.37 |
| UP_40 | 69 | 20 | 62735.39 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
