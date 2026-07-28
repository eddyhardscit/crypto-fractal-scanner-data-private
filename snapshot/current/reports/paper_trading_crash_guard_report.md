# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T13:38:41+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **23**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **143.26 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 67 | 0 | 7828.02 |
| DOWN_20 | 67 | 0 | 15656.03 |
| DOWN_30 | 67 | 7 | 23567.99 |
| DOWN_40 | 67 | 14 | 29929.62 |
| UP_10 | 282 | 0 | 34981.96 |
| UP_20 | 282 | 0 | 69963.92 |
| UP_30 | 282 | 0 | 104945.88 |
| UP_40 | 282 | 137 | 125477.03 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
