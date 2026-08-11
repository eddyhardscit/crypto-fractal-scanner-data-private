# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T01:09:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **10**
- Simulazioni bloccate attive: **29**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **215.58 R**
- Profitto virtuale mancato: **318.05 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 97 | 0 | 18071.86 |
| DOWN_20 | 97 | 0 | 36143.72 |
| DOWN_30 | 97 | 0 | 54215.59 |
| DOWN_40 | 97 | 29 | 67412.54 |
| UP_10 | 64 | 0 | 15085.92 |
| UP_20 | 64 | 0 | 30171.84 |
| UP_30 | 64 | 0 | 45257.75 |
| UP_40 | 64 | 13 | 57740.24 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
