# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T05:38:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **41**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **163.54 R**
- Profitto virtuale mancato: **260.98 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 107 | 0 | 10529.14 |
| DOWN_20 | 107 | 0 | 21058.28 |
| DOWN_30 | 107 | 0 | 31587.42 |
| DOWN_40 | 107 | 18 | 40596.38 |
| UP_10 | 256 | 0 | 36713.74 |
| UP_20 | 256 | 0 | 73427.49 |
| UP_30 | 256 | 0 | 110141.23 |
| UP_40 | 256 | 146 | 129955.67 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
