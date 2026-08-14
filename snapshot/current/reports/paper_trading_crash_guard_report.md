# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T02:07:18+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **67**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **519.19 R**
- Profitto virtuale mancato: **506.35 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 214 | 0 | 29538.28 |
| DOWN_20 | 214 | 0 | 59076.57 |
| DOWN_30 | 214 | 1 | 88628.04 |
| DOWN_40 | 214 | 56 | 114041.19 |
| UP_10 | 165 | 0 | 33106.21 |
| UP_20 | 165 | 0 | 66212.42 |
| UP_30 | 165 | 0 | 99318.62 |
| UP_40 | 165 | 70 | 120835.69 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
