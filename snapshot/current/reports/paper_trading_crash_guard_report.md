# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T22:39:11+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **69**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **393.86 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 151 | 0 | 19294.63 |
| DOWN_20 | 151 | 0 | 38589.26 |
| DOWN_30 | 151 | 0 | 57883.90 |
| DOWN_40 | 151 | 38 | 74422.14 |
| UP_10 | 96 | 0 | 28477.25 |
| UP_20 | 96 | 0 | 56954.51 |
| UP_30 | 96 | 0 | 85431.76 |
| UP_40 | 96 | 54 | 101805.82 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
