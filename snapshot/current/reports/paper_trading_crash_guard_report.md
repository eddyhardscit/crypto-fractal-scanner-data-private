# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-28T20:53:41+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **9**
- Simulazioni completate nel ciclo: **0**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **212.97 R**
- Profitto virtuale mancato: **287.32 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 118 | 0 | 13726.78 |
| DOWN_20 | 118 | 23 | 28695.01 |
| DOWN_30 | 118 | 23 | 41490.71 |
| DOWN_40 | 118 | 83 | 49798.37 |
| UP_10 | 151 | 0 | 14123.52 |
| UP_20 | 151 | 9 | 28762.32 |
| UP_30 | 151 | 10 | 42582.66 |
| UP_40 | 151 | 68 | 53394.09 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
