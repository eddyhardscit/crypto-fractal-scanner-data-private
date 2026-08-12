# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T11:39:15+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **86**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **349.42 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 141 | 0 | 31763.34 |
| DOWN_20 | 141 | 0 | 63526.68 |
| DOWN_30 | 141 | 0 | 95290.03 |
| DOWN_40 | 141 | 40 | 120063.38 |
| UP_10 | 87 | 0 | 25938.07 |
| UP_20 | 87 | 0 | 51876.14 |
| UP_30 | 87 | 0 | 77814.21 |
| UP_40 | 87 | 33 | 95242.25 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
