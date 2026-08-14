# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T11:08:29+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **17**
- Simulazioni bloccate attive: **76**
- Simulazioni completate nel ciclo: **54**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **566.73 R**
- Profitto virtuale mancato: **544.66 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 239 | 0 | 20217.42 |
| DOWN_20 | 239 | 0 | 40434.84 |
| DOWN_30 | 239 | 0 | 60652.27 |
| DOWN_40 | 239 | 61 | 77756.46 |
| UP_10 | 164 | 0 | 35054.04 |
| UP_20 | 164 | 0 | 70108.08 |
| UP_30 | 164 | 2 | 105177.53 |
| UP_40 | 164 | 72 | 127627.90 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
