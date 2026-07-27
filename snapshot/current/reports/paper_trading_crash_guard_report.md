# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T12:08:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **4**
- Simulazioni bloccate attive: **16**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **149.88 R**
- Profitto virtuale mancato: **259.49 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 282 | 0 | 33077.31 |
| DOWN_20 | 282 | 0 | 66154.62 |
| DOWN_30 | 282 | 1 | 99232.82 |
| DOWN_40 | 282 | 114 | 122898.81 |
| UP_10 | 97 | 0 | 12945.37 |
| UP_20 | 97 | 1 | 25890.74 |
| UP_30 | 97 | 1 | 38719.37 |
| UP_40 | 97 | 51 | 46547.59 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
