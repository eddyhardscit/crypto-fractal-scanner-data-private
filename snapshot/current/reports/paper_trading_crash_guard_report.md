# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T09:08:41+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **11**
- Simulazioni bloccate attive: **12**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **149.88 R**
- Profitto virtuale mancato: **259.49 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 271 | 0 | 32582.86 |
| DOWN_20 | 271 | 0 | 65165.72 |
| DOWN_30 | 271 | 1 | 97749.46 |
| DOWN_40 | 271 | 120 | 119518.90 |
| UP_10 | 99 | 2 | 13193.70 |
| UP_20 | 99 | 2 | 26327.39 |
| UP_30 | 99 | 3 | 39344.34 |
| UP_40 | 99 | 53 | 47360.89 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
