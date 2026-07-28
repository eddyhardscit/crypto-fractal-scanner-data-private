# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T17:53:40+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **190.75 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 106 | 0 | 13146.71 |
| DOWN_20 | 106 | 0 | 26293.41 |
| DOWN_30 | 106 | 23 | 39750.48 |
| DOWN_40 | 106 | 45 | 47047.34 |
| UP_10 | 145 | 0 | 13941.14 |
| UP_20 | 145 | 0 | 27882.29 |
| UP_30 | 145 | 0 | 41823.43 |
| UP_40 | 145 | 48 | 52458.18 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
