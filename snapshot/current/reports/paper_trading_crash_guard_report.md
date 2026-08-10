# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-10T22:09:24+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **23**
- Simulazioni bloccate attive: **48**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **196.29 R**
- Profitto virtuale mancato: **312.09 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 80 | 0 | 14183.89 |
| DOWN_20 | 80 | 0 | 28367.79 |
| DOWN_30 | 80 | 0 | 42551.68 |
| DOWN_40 | 80 | 20 | 52986.63 |
| UP_10 | 19 | 0 | 5753.09 |
| UP_20 | 19 | 0 | 11506.18 |
| UP_30 | 19 | 0 | 17259.27 |
| UP_40 | 19 | 4 | 22348.18 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
