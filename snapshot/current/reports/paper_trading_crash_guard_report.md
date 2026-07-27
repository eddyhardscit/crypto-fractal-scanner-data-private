# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-27T13:22:33+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **5**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **160.99 R**
- Profitto virtuale mancato: **259.49 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 254 | 0 | 28990.76 |
| DOWN_20 | 254 | 0 | 57981.53 |
| DOWN_30 | 254 | 1 | 86973.18 |
| DOWN_40 | 254 | 93 | 108132.69 |
| UP_10 | 95 | 0 | 12431.42 |
| UP_20 | 95 | 0 | 24862.84 |
| UP_30 | 95 | 0 | 37294.26 |
| UP_40 | 95 | 50 | 44725.27 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
