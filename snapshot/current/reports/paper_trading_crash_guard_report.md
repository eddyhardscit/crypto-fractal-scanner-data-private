# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-11T02:09:22+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **12**
- Simulazioni completate nel ciclo: **4**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **180.95 R**
- Profitto virtuale mancato: **352.68 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 107 | 0 | 18554.36 |
| DOWN_20 | 107 | 0 | 37108.71 |
| DOWN_30 | 107 | 0 | 55663.07 |
| DOWN_40 | 107 | 39 | 69020.85 |
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
