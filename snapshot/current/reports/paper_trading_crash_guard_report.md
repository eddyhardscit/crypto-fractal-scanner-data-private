# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T01:23:41+00:00

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
| DOWN_10 | 109 | 0 | 11898.60 |
| DOWN_20 | 109 | 0 | 23797.20 |
| DOWN_30 | 109 | 0 | 35695.81 |
| DOWN_40 | 109 | 22 | 45755.08 |
| UP_10 | 254 | 0 | 37664.27 |
| UP_20 | 254 | 0 | 75328.54 |
| UP_30 | 254 | 0 | 112992.81 |
| UP_40 | 254 | 142 | 133335.54 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
