# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-14T05:06:34+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **20**
- Simulazioni bloccate attive: **79**
- Simulazioni completate nel ciclo: **8**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **503.27 R**
- Profitto virtuale mancato: **522.27 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 189 | 0 | 19271.16 |
| DOWN_20 | 189 | 0 | 38542.32 |
| DOWN_30 | 189 | 3 | 57853.72 |
| DOWN_40 | 189 | 47 | 75291.22 |
| UP_10 | 164 | 0 | 32540.89 |
| UP_20 | 164 | 0 | 65081.77 |
| UP_30 | 164 | 0 | 97622.66 |
| UP_40 | 164 | 61 | 118951.29 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
