# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T12:39:02+00:00

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
| DOWN_10 | 163 | 0 | 34273.53 |
| DOWN_20 | 163 | 0 | 68547.05 |
| DOWN_30 | 163 | 0 | 102820.58 |
| DOWN_40 | 163 | 50 | 129580.45 |
| UP_10 | 70 | 0 | 21179.34 |
| UP_20 | 70 | 0 | 42358.68 |
| UP_30 | 70 | 0 | 63538.02 |
| UP_40 | 70 | 29 | 76985.54 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
