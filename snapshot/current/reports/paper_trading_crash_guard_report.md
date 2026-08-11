# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T12:09:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **12**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **141.06 R**
- Profitto virtuale mancato: **392.57 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 161 | 0 | 27073.65 |
| DOWN_20 | 161 | 0 | 54147.29 |
| DOWN_30 | 161 | 0 | 81220.94 |
| DOWN_40 | 161 | 53 | 101779.60 |
| UP_10 | 101 | 0 | 18660.02 |
| UP_20 | 101 | 0 | 37320.03 |
| UP_30 | 101 | 1 | 55980.94 |
| UP_40 | 101 | 25 | 71292.43 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
