# Blocco 4.5 — Crash Cascade Guard

Generato: 2026-08-12T01:24:07+00:00

> Paper-only. In mercato NORMAL/WATCH non riduce i segnali. Le limitazioni iniziano soltanto in STRESS, RECOVERY, CRASH, EXTREME o con dati non affidabili.

## Stato corrente

- Livello: **NORMAL**
- Direzione: **NONE**
- Segnali bloccati nel ciclo: **0**
- Simulazioni bloccate attive: **94**
- Simulazioni completate nel ciclo: **32**
- Liquidazioni virtuali evitate totali: **0**
- Valore cumulato del filtro: **303.97 R**
- Profitto virtuale mancato: **439.74 R**

## Stress test portafogli Paper

| Scenario | Posizioni interessate | Liquidazioni stimate | Perdita stimata EUR |
| --- | ---: | ---: | ---: |
| DOWN_10 | 130 | 0 | 19713.60 |
| DOWN_20 | 130 | 0 | 39427.20 |
| DOWN_30 | 130 | 6 | 59222.46 |
| DOWN_40 | 130 | 40 | 73875.58 |
| UP_10 | 148 | 0 | 28277.22 |
| UP_20 | 148 | 0 | 56554.43 |
| UP_30 | 148 | 2 | 84860.68 |
| UP_40 | 148 | 66 | 102102.83 |

## Modello di esecuzione

Se una candela di cascata attraversa nello stesso intervallo sia lo stop sia il prezzo di liquidazione, il Paper usa il caso peggiore e registra una liquidazione intrabar. Gli stop in gap o in regime di stress ricevono slippage aggiuntivo.

## Requisiti prima del live futures

- modalità ISOLATED obbligatoria;
- stop nativo sull'exchange;
- conferma dello stop prima di accettare la posizione;
- cross margin vietato.
