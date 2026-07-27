# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T08:08:38+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **59**
- Simulazioni bloccate attive: **172**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-17.73 R**
- Profitto virtuale mancato: **256.41 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 227 | 2 | 29399.37 |
| DOWN_20 | 227 | 3 | 58738.73 |
| DOWN_30 | 227 | 5 | 88084.30 |
| DOWN_40 | 227 | 92 | 108862.17 |
| UP_10 | 99 | 2 | 13193.70 |
| UP_20 | 99 | 3 | 26327.39 |
| UP_30 | 99 | 3 | 39344.34 |
| UP_40 | 99 | 53 | 47360.89 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
