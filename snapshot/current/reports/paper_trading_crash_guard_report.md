# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-20T10:23:31+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **1**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **3.03 R**
- Profitto virtuale mancato: **0.00 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 30 | 0 | 4165.02 |
| DOWN_20 | 30 | 0 | 8330.03 |
| DOWN_30 | 30 | 1 | 12524.45 |
| DOWN_40 | 30 | 7 | 15676.31 |
| UP_10 | 37 | 0 | 7076.04 |
| UP_20 | 37 | 0 | 14152.09 |
| UP_30 | 37 | 1 | 21259.46 |
| UP_40 | 37 | 17 | 25436.86 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
