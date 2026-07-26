# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-26T03:38:37+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **67**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **22.58 R**
- Profitto virtuale mancato: **150.37 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 281 | 0 | 22615.78 |
| DOWN_20 | 281 | 0 | 45231.57 |
| DOWN_30 | 281 | 0 | 67847.35 |
| DOWN_40 | 281 | 106 | 84961.26 |
| UP_10 | 83 | 0 | 13286.29 |
| UP_20 | 83 | 0 | 26572.59 |
| UP_30 | 83 | 3 | 39910.29 |
| UP_40 | 83 | 33 | 47406.53 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
