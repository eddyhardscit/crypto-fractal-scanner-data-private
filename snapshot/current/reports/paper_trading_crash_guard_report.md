# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T04:54:07+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **67**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **435.83 R**
- Profitto virtuale mancato: **504.86 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 136 | 0 | 21964.30 |
| DOWN_20 | 136 | 0 | 43928.60 |
| DOWN_30 | 136 | 0 | 65892.89 |
| DOWN_40 | 136 | 48 | 85028.87 |
| UP_10 | 140 | 0 | 31504.66 |
| UP_20 | 140 | 0 | 63009.33 |
| UP_30 | 140 | 0 | 94513.99 |
| UP_40 | 140 | 58 | 114908.18 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
