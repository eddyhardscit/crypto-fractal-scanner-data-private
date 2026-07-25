# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-07-25T06:08:39+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **3**
- Simulazioni bloccate attive: **20**
- Simulazioni completate nel ciclo: **20**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **-51.07 R**
- Profitto virtuale mancato: **107.69 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 145 | 0 | 13489.97 |
| DOWN_20 | 145 | 0 | 26979.93 |
| DOWN_30 | 145 | 0 | 40469.90 |
| DOWN_40 | 145 | 33 | 51283.66 |
| UP_10 | 59 | 0 | 15871.64 |
| UP_20 | 59 | 0 | 31743.28 |
| UP_30 | 59 | 0 | 47614.92 |
| UP_40 | 59 | 34 | 56273.41 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
