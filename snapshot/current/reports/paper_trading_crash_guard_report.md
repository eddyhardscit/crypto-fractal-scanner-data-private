# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-24T13:53:55+00:00

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
| DOWN_10 | 117 | 0 | 12934.07 |
| DOWN_20 | 117 | 0 | 25868.13 |
| DOWN_30 | 117 | 11 | 38955.74 |
| DOWN_40 | 117 | 31 | 49247.37 |
| UP_10 | 66 | 0 | 18795.21 |
| UP_20 | 66 | 0 | 37590.42 |
| UP_30 | 66 | 0 | 56385.64 |
| UP_40 | 66 | 37 | 67082.89 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
