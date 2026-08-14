# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T00:10:13+00:00

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
| DOWN_30 | 220 | 0 | 89405.19 |
| DOWN_40 | 220 | 68 | 114893.69 |
| UP_10 | 162 | 0 | 32977.61 |
| UP_20 | 162 | 0 | 65955.21 |
| UP_30 | 162 | 0 | 98932.82 |
| UP_40 | 162 | 67 | 120407.02 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
