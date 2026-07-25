# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T22:38:40+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **69**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-41.14 R**
- Profitto virtuale mancato: **144.40 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 259 | 0 | 22726.17 |
| DOWN_20 | 259 | 0 | 45452.34 |
| DOWN_30 | 259 | 36 | 68740.44 |
| DOWN_40 | 259 | 104 | 85084.29 |
| UP_10 | 99 | 0 | 19253.07 |
| UP_20 | 99 | 2 | 38506.13 |
| UP_30 | 99 | 12 | 57486.70 |
| UP_40 | 99 | 57 | 68668.55 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
