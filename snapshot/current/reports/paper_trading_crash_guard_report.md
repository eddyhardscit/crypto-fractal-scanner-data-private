# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T12:53:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **16**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-39.46 R**
- Profitto virtuale mancato: **77.89 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 116 | 0 | 13492.64 |
| DOWN_20 | 116 | 0 | 26985.28 |
| DOWN_30 | 116 | 0 | 40477.91 |
| DOWN_40 | 116 | 28 | 51314.43 |
| UP_10 | 67 | 0 | 19263.87 |
| UP_20 | 67 | 0 | 38527.74 |
| UP_30 | 67 | 0 | 57791.61 |
| UP_40 | 67 | 37 | 68774.22 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
