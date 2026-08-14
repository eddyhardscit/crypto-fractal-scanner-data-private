# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T01:07:05+00:00

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
| DOWN_10 | 220 | 0 | 29801.73 |
| DOWN_20 | 220 | 0 | 59603.46 |
| DOWN_30 | 220 | 5 | 89474.44 |
| DOWN_40 | 220 | 68 | 114893.69 |
| UP_10 | 163 | 0 | 33019.77 |
| UP_20 | 163 | 0 | 66039.54 |
| UP_30 | 163 | 0 | 99059.31 |
| UP_40 | 163 | 68 | 120547.57 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
