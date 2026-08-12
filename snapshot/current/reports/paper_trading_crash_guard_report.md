# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T05:24:00+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **94**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **303.97 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 88 | 0 | 17961.56 |
| DOWN_20 | 88 | 0 | 35923.12 |
| DOWN_30 | 88 | 2 | 53913.46 |
| DOWN_40 | 88 | 33 | 67113.93 |
| UP_10 | 147 | 0 | 26355.41 |
| UP_20 | 147 | 2 | 52826.94 |
| UP_30 | 147 | 10 | 79207.89 |
| UP_40 | 147 | 84 | 95383.16 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
