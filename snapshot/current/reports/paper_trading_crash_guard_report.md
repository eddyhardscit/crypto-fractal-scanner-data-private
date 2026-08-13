# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-13T11:08:26+00:00

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
| DOWN_10 | 167 | 0 | 29246.50 |
| DOWN_20 | 167 | 0 | 58493.00 |
| DOWN_30 | 167 | 0 | 87739.51 |
| DOWN_40 | 167 | 59 | 112190.95 |
| UP_10 | 141 | 0 | 31775.51 |
| UP_20 | 141 | 0 | 63551.02 |
| UP_30 | 141 | 0 | 95326.53 |
| UP_40 | 141 | 57 | 116017.79 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
