# Sequenze pratiche: rimbalzo dopo discesa / dump dopo spike

Generato: **2026-08-14 07:36:04 CEST**  
UTC: **2026-08-14 05:36:04 UTC**

Questo report guarda l'ordine degli eventi nei 40 casi storici più simili.

- **Prima scende → poi rimbalza**: utile per capire se una discesa può diventare zona di rimbalzo.
- **Prima sale → poi scarica**: utile per capire se una salita forte può diventare zona da prendere profitto.

## Lettura pratica veloce

| Asset | Se scende a -5% | Target +10% | % casi | Movimento reale | Lettura discesa | Se sale a +10% | Target -5% | % casi | Movimento reale | Lettura spike |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BTC | 60.087 $ | 69.575 $ | +38,46% | +15,79% | rimbalzo debole | 69.575 $ | 60.087 $ | +6,67% | -13,64% | spike storicamente più resistente |
| SOL | 72,01 $ | 83,38 $ | +37,50% | +15,79% | rimbalzo debole | 83,38 $ | 72,01 $ | 0,00% | -13,64% | spike storicamente più resistente |
| DOGE | 0,06644 $ | 0,07693 $ | +62,07% | +15,79% | rimbalzo possibile | 0,07693 $ | 0,06644 $ | +12,90% | -13,64% | spike storicamente più resistente |

## Spiegazione semplice delle percentuali

Queste percentuali sono **condizionate**.

Vuol dire che il report controlla sempre due passaggi, in ordine:

1. Prima deve succedere la prima cosa.
2. Solo dopo si controlla se succede la seconda cosa.

### Esempio rimbalzo

`Se scende a -5% → poi +10% = 24%`

Vuol dire:

- Lo scanner prende i 40 casi storici più simili.
- Prima guarda quanti sono scesi almeno a -5% dal prezzo iniziale.
- Poi, solo tra quelli che sono scesi, guarda quanti sono arrivati a +10% dal prezzo iniziale.
- Se il risultato è 24%, vuol dire circa 1 caso su 4.

Esempio con prezzo iniziale 100 $:

- -5% = 95 $
- +10% = 110 $
- il movimento reale da 95 $ a 110 $ non è +10%, ma circa +15,79%.

Quindi `poi +10%` non significa +10% dal minimo. Significa +10% dal prezzo iniziale.

### Esempio dump dopo spike

`Se sale a +10% → poi dump -5% = 62%`

Vuol dire:

- Prima il prezzo deve salire almeno a +10% dal prezzo iniziale.
- Poi si controlla se, dopo quello spike, scende fino a -5% dal prezzo iniziale.
- Se il risultato è 62%, vuol dire che questo scarico è successo più di metà delle volte.

Esempio con prezzo iniziale 100 $:

- +10% = 110 $
- -5% = 95 $
- il movimento reale da 110 $ a 95 $ non è -5%, ma circa -13,64%.

Quindi `dump -5%` non significa -5% dallo spike. Significa che torna fino a 5% sotto il prezzo iniziale.

### Soglie controllate

Nel report principale vedi solo la lettura più semplice:

- discesa -5% → rimbalzo +10%
- spike +10% → dump -5%

Nel report dettagliato invece lo scanner controlla anche soglie intermedie:

- discese: -5%, -8%, -10%, -15%
- rimbalzi: +5%, +10%, +15%, +20%
- spike: +5%, +10%, +15%, +20%
- dump: 0%, -5%, -8%, -10%, -15%

---

# Bitcoin — BTC

## Lettura semplice

- BTC: su 40 casi simili, 13 prima sono scesi a -5,00%. Tra quei 13, 5 poi sono rimbalzati fino a +10,00%. Percentuale: +38,46% (5/13). Dal livello -5,00% al target +10,00% il movimento reale sarebbe circa +15,79%. Lettura: rimbalzo debole.
- BTC: su 40 casi simili, 30 prima sono saliti a +10,00%. Tra quei 30, 2 poi sono scaricati a -5,00%. Percentuale: +6,67% (2/30). Dal livello +10,00% al target -5,00% il movimento reale sarebbe circa -13,64%. Lettura: spike storicamente più resistente.

## Tabella rimbalzo dopo discesa

| Prima scende | Prezzo | Casi scesi | % casi scesi | Poi rimbalza a | Prezzo target | Casi riusciti | % riusciti | Movimento reale | Forza | Giorni discesa | Giorni target |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| -5,00% | 60.087 $ | 13/40 | +32,50% | +5,00% | 66.412 $ | 8/13 | +61,54% | +10,53% | MEDIA | 8,4 | 18,1 |
| -5,00% | 60.087 $ | 13/40 | +32,50% | +10,00% | 69.575 $ | 5/13 | +38,46% | +15,79% | BASSA | 8,4 | 19,0 |
| -5,00% | 60.087 $ | 13/40 | +32,50% | +15,00% | 72.737 $ | 4/13 | +30,77% | +21,05% | DEBOLE | 8,4 | 19,8 |
| -5,00% | 60.087 $ | 13/40 | +32,50% | +20,00% | 75.900 $ | 2/13 | +15,38% | +26,32% | DEBOLE | 8,4 | 17,5 |
| -8,00% | 58.190 $ | 7/40 | +17,50% | +5,00% | 66.412 $ | 3/7 | +42,86% | +14,13% | BASSA | 11,7 | 26,3 |
| -8,00% | 58.190 $ | 7/40 | +17,50% | +10,00% | 69.575 $ | 2/7 | +28,57% | +19,57% | DEBOLE | 11,7 | 25,0 |
| -8,00% | 58.190 $ | 7/40 | +17,50% | +15,00% | 72.737 $ | 1/7 | +14,29% | +25,00% | DEBOLE | 11,7 | 29,0 |
| -8,00% | 58.190 $ | 7/40 | +17,50% | +20,00% | 75.900 $ | 0/7 | 0,00% | +30,43% | DEBOLE | 11,7 | n/d |
| -10,00% | 56.925 $ | 7/40 | +17,50% | +5,00% | 66.412 $ | 3/7 | +42,86% | +16,67% | BASSA | 14,0 | 26,3 |
| -10,00% | 56.925 $ | 7/40 | +17,50% | +10,00% | 69.575 $ | 2/7 | +28,57% | +22,22% | DEBOLE | 14,0 | 25,0 |
| -10,00% | 56.925 $ | 7/40 | +17,50% | +15,00% | 72.737 $ | 1/7 | +14,29% | +27,78% | DEBOLE | 14,0 | 29,0 |
| -10,00% | 56.925 $ | 7/40 | +17,50% | +20,00% | 75.900 $ | 0/7 | 0,00% | +33,33% | DEBOLE | 14,0 | n/d |
| -15,00% | 53.762 $ | 6/40 | +15,00% | +5,00% | 66.412 $ | 2/6 | +33,33% | +23,53% | DEBOLE | 16,0 | 24,5 |
| -15,00% | 53.762 $ | 6/40 | +15,00% | +10,00% | 69.575 $ | 2/6 | +33,33% | +29,41% | DEBOLE | 16,0 | 25,0 |
| -15,00% | 53.762 $ | 6/40 | +15,00% | +15,00% | 72.737 $ | 1/6 | +16,67% | +35,29% | DEBOLE | 16,0 | 29,0 |
| -15,00% | 53.762 $ | 6/40 | +15,00% | +20,00% | 75.900 $ | 0/6 | 0,00% | +41,18% | DEBOLE | 16,0 | n/d |

## Tabella dump dopo spike

| Prima sale | Prezzo spike | Casi spike | % casi spike | Poi scarica a | Prezzo target | Casi scarico | % scarico | Movimento reale | Forza | Giorni spike | Giorni dump |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| +5,00% | 66.412 $ | 36/40 | +90,00% | prezzo iniziale | 63.250 $ | 11/36 | +30,56% | -4,76% | DEBOLE | 7,1 | 16,9 |
| +5,00% | 66.412 $ | 36/40 | +90,00% | -5,00% | 60.087 $ | 4/36 | +11,11% | -9,52% | DEBOLE | 7,1 | 18,5 |
| +5,00% | 66.412 $ | 36/40 | +90,00% | -8,00% | 58.190 $ | 3/36 | +8,33% | -12,38% | DEBOLE | 7,1 | 15,0 |
| +5,00% | 66.412 $ | 36/40 | +90,00% | -10,00% | 56.925 $ | 3/36 | +8,33% | -14,29% | DEBOLE | 7,1 | 19,0 |
| +5,00% | 66.412 $ | 36/40 | +90,00% | -15,00% | 53.762 $ | 2/36 | +5,56% | -19,05% | DEBOLE | 7,1 | 22,5 |
| +10,00% | 69.575 $ | 30/40 | +75,00% | prezzo iniziale | 63.250 $ | 3/30 | +10,00% | -9,09% | DEBOLE | 13,8 | 28,0 |
| +10,00% | 69.575 $ | 30/40 | +75,00% | -5,00% | 60.087 $ | 2/30 | +6,67% | -13,64% | DEBOLE | 13,8 | 28,5 |
| +10,00% | 69.575 $ | 30/40 | +75,00% | -8,00% | 58.190 $ | 1/30 | +3,33% | -16,36% | DEBOLE | 13,8 | 28,0 |
| +10,00% | 69.575 $ | 30/40 | +75,00% | -10,00% | 56.925 $ | 1/30 | +3,33% | -18,18% | DEBOLE | 13,8 | 28,0 |
| +10,00% | 69.575 $ | 30/40 | +75,00% | -15,00% | 53.762 $ | 1/30 | +3,33% | -22,73% | DEBOLE | 13,8 | 28,0 |
| +15,00% | 72.737 $ | 25/40 | +62,50% | prezzo iniziale | 63.250 $ | 2/25 | +8,00% | -13,04% | DEBOLE | 14,1 | 28,0 |
| +15,00% | 72.737 $ | 25/40 | +62,50% | -5,00% | 60.087 $ | 1/25 | +4,00% | -17,39% | DEBOLE | 14,1 | 27,0 |
| +15,00% | 72.737 $ | 25/40 | +62,50% | -8,00% | 58.190 $ | 1/25 | +4,00% | -20,00% | DEBOLE | 14,1 | 28,0 |
| +15,00% | 72.737 $ | 25/40 | +62,50% | -10,00% | 56.925 $ | 1/25 | +4,00% | -21,74% | DEBOLE | 14,1 | 28,0 |
| +15,00% | 72.737 $ | 25/40 | +62,50% | -15,00% | 53.762 $ | 1/25 | +4,00% | -26,09% | DEBOLE | 14,1 | 28,0 |
| +20,00% | 75.900 $ | 18/40 | +45,00% | prezzo iniziale | 63.250 $ | 1/18 | +5,56% | -16,67% | DEBOLE | 12,4 | 27,0 |
| +20,00% | 75.900 $ | 18/40 | +45,00% | -5,00% | 60.087 $ | 1/18 | +5,56% | -20,83% | DEBOLE | 12,4 | 27,0 |
| +20,00% | 75.900 $ | 18/40 | +45,00% | -8,00% | 58.190 $ | 1/18 | +5,56% | -23,33% | DEBOLE | 12,4 | 28,0 |
| +20,00% | 75.900 $ | 18/40 | +45,00% | -10,00% | 56.925 $ | 1/18 | +5,56% | -25,00% | DEBOLE | 12,4 | 28,0 |
| +20,00% | 75.900 $ | 18/40 | +45,00% | -15,00% | 53.762 $ | 1/18 | +5,56% | -29,17% | DEBOLE | 12,4 | 28,0 |

---

# Solana — SOL

## Lettura semplice

- SOL: su 40 casi simili, 16 prima sono scesi a -5,00%. Tra quei 16, 6 poi sono rimbalzati fino a +10,00%. Percentuale: +37,50% (6/16). Dal livello -5,00% al target +10,00% il movimento reale sarebbe circa +15,79%. Lettura: rimbalzo debole.
- SOL: su 40 casi simili, 26 prima sono saliti a +10,00%. Tra quei 26, 0 poi sono scaricati a -5,00%. Percentuale: 0,00% (0/26). Dal livello +10,00% al target -5,00% il movimento reale sarebbe circa -13,64%. Lettura: spike storicamente più resistente.

## Tabella rimbalzo dopo discesa

| Prima scende | Prezzo | Casi scesi | % casi scesi | Poi rimbalza a | Prezzo target | Casi riusciti | % riusciti | Movimento reale | Forza | Giorni discesa | Giorni target |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| -5,00% | 72,01 $ | 16/40 | +40,00% | +5,00% | 79,59 $ | 9/16 | +56,25% | +10,53% | MEDIA | 8,3 | 15,6 |
| -5,00% | 72,01 $ | 16/40 | +40,00% | +10,00% | 83,38 $ | 6/16 | +37,50% | +15,79% | BASSA | 8,3 | 19,0 |
| -5,00% | 72,01 $ | 16/40 | +40,00% | +15,00% | 87,17 $ | 4/16 | +25,00% | +21,05% | DEBOLE | 8,3 | 19,0 |
| -5,00% | 72,01 $ | 16/40 | +40,00% | +20,00% | 90,96 $ | 2/16 | +12,50% | +26,32% | DEBOLE | 8,3 | 20,5 |
| -8,00% | 69,74 $ | 8/40 | +20,00% | +5,00% | 79,59 $ | 3/8 | +37,50% | +14,13% | BASSA | 12,1 | 17,3 |
| -8,00% | 69,74 $ | 8/40 | +20,00% | +10,00% | 83,38 $ | 2/8 | +25,00% | +19,57% | DEBOLE | 12,1 | 23,5 |
| -8,00% | 69,74 $ | 8/40 | +20,00% | +15,00% | 87,17 $ | 1/8 | +12,50% | +25,00% | DEBOLE | 12,1 | 18,0 |
| -8,00% | 69,74 $ | 8/40 | +20,00% | +20,00% | 90,96 $ | 1/8 | +12,50% | +30,43% | DEBOLE | 12,1 | 18,0 |
| -10,00% | 68,22 $ | 7/40 | +17,50% | +5,00% | 79,59 $ | 3/7 | +42,86% | +16,67% | BASSA | 14,9 | 17,3 |
| -10,00% | 68,22 $ | 7/40 | +17,50% | +10,00% | 83,38 $ | 2/7 | +28,57% | +22,22% | DEBOLE | 14,9 | 23,5 |
| -10,00% | 68,22 $ | 7/40 | +17,50% | +15,00% | 87,17 $ | 1/7 | +14,29% | +27,78% | DEBOLE | 14,9 | 18,0 |
| -10,00% | 68,22 $ | 7/40 | +17,50% | +20,00% | 90,96 $ | 1/7 | +14,29% | +33,33% | DEBOLE | 14,9 | 18,0 |
| -15,00% | 64,43 $ | 4/40 | +10,00% | +5,00% | 79,59 $ | 1/4 | +25,00% | +23,53% | DEBOLE | 15,8 | 16,0 |
| -15,00% | 64,43 $ | 4/40 | +10,00% | +10,00% | 83,38 $ | 1/4 | +25,00% | +29,41% | DEBOLE | 15,8 | 30,0 |
| -15,00% | 64,43 $ | 4/40 | +10,00% | +15,00% | 87,17 $ | 0/4 | 0,00% | +35,29% | DEBOLE | 15,8 | n/d |
| -15,00% | 64,43 $ | 4/40 | +10,00% | +20,00% | 90,96 $ | 0/4 | 0,00% | +41,18% | DEBOLE | 15,8 | n/d |

## Tabella dump dopo spike

| Prima sale | Prezzo spike | Casi spike | % casi spike | Poi scarica a | Prezzo target | Casi scarico | % scarico | Movimento reale | Forza | Giorni spike | Giorni dump |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| +5,00% | 79,59 $ | 34/40 | +85,00% | prezzo iniziale | 75,80 $ | 9/34 | +26,47% | -4,76% | DEBOLE | 7,7 | 21,1 |
| +5,00% | 79,59 $ | 34/40 | +85,00% | -5,00% | 72,01 $ | 3/34 | +8,82% | -9,52% | DEBOLE | 7,7 | 23,0 |
| +5,00% | 79,59 $ | 34/40 | +85,00% | -8,00% | 69,74 $ | 0/34 | 0,00% | -12,38% | DEBOLE | 7,7 | n/d |
| +5,00% | 79,59 $ | 34/40 | +85,00% | -10,00% | 68,22 $ | 0/34 | 0,00% | -14,29% | DEBOLE | 7,7 | n/d |
| +5,00% | 79,59 $ | 34/40 | +85,00% | -15,00% | 64,43 $ | 0/34 | 0,00% | -19,05% | DEBOLE | 7,7 | n/d |
| +10,00% | 83,38 $ | 26/40 | +65,00% | prezzo iniziale | 75,80 $ | 2/26 | +7,69% | -9,09% | DEBOLE | 9,3 | 27,0 |
| +10,00% | 83,38 $ | 26/40 | +65,00% | -5,00% | 72,01 $ | 0/26 | 0,00% | -13,64% | DEBOLE | 9,3 | n/d |
| +10,00% | 83,38 $ | 26/40 | +65,00% | -8,00% | 69,74 $ | 0/26 | 0,00% | -16,36% | DEBOLE | 9,3 | n/d |
| +10,00% | 83,38 $ | 26/40 | +65,00% | -10,00% | 68,22 $ | 0/26 | 0,00% | -18,18% | DEBOLE | 9,3 | n/d |
| +10,00% | 83,38 $ | 26/40 | +65,00% | -15,00% | 64,43 $ | 0/26 | 0,00% | -22,73% | DEBOLE | 9,3 | n/d |
| +15,00% | 87,17 $ | 23/40 | +57,50% | prezzo iniziale | 75,80 $ | 1/23 | +4,35% | -13,04% | DEBOLE | 10,5 | 29,0 |
| +15,00% | 87,17 $ | 23/40 | +57,50% | -5,00% | 72,01 $ | 0/23 | 0,00% | -17,39% | DEBOLE | 10,5 | n/d |
| +15,00% | 87,17 $ | 23/40 | +57,50% | -8,00% | 69,74 $ | 0/23 | 0,00% | -20,00% | DEBOLE | 10,5 | n/d |
| +15,00% | 87,17 $ | 23/40 | +57,50% | -10,00% | 68,22 $ | 0/23 | 0,00% | -21,74% | DEBOLE | 10,5 | n/d |
| +15,00% | 87,17 $ | 23/40 | +57,50% | -15,00% | 64,43 $ | 0/23 | 0,00% | -26,09% | DEBOLE | 10,5 | n/d |
| +20,00% | 90,96 $ | 18/40 | +45,00% | prezzo iniziale | 75,80 $ | 0/18 | 0,00% | -16,67% | DEBOLE | 10,2 | n/d |
| +20,00% | 90,96 $ | 18/40 | +45,00% | -5,00% | 72,01 $ | 0/18 | 0,00% | -20,83% | DEBOLE | 10,2 | n/d |
| +20,00% | 90,96 $ | 18/40 | +45,00% | -8,00% | 69,74 $ | 0/18 | 0,00% | -23,33% | DEBOLE | 10,2 | n/d |
| +20,00% | 90,96 $ | 18/40 | +45,00% | -10,00% | 68,22 $ | 0/18 | 0,00% | -25,00% | DEBOLE | 10,2 | n/d |
| +20,00% | 90,96 $ | 18/40 | +45,00% | -15,00% | 64,43 $ | 0/18 | 0,00% | -29,17% | DEBOLE | 10,2 | n/d |

---

# Dogecoin — DOGE

## Lettura semplice

- DOGE: su 40 casi simili, 29 prima sono scesi a -5,00%. Tra quei 29, 18 poi sono rimbalzati fino a +10,00%. Percentuale: +62,07% (18/29). Dal livello -5,00% al target +10,00% il movimento reale sarebbe circa +15,79%. Lettura: rimbalzo possibile.
- DOGE: su 40 casi simili, 31 prima sono saliti a +10,00%. Tra quei 31, 4 poi sono scaricati a -5,00%. Percentuale: +12,90% (4/31). Dal livello +10,00% al target -5,00% il movimento reale sarebbe circa -13,64%. Lettura: spike storicamente più resistente.

## Tabella rimbalzo dopo discesa

| Prima scende | Prezzo | Casi scesi | % casi scesi | Poi rimbalza a | Prezzo target | Casi riusciti | % riusciti | Movimento reale | Forza | Giorni discesa | Giorni target |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| -5,00% | 0,06644 $ | 29/40 | +72,50% | +5,00% | 0,07344 $ | 18/29 | +62,07% | +10,53% | MEDIA | 5,5 | 12,9 |
| -5,00% | 0,06644 $ | 29/40 | +72,50% | +10,00% | 0,07693 $ | 18/29 | +62,07% | +15,79% | MEDIA | 5,5 | 15,3 |
| -5,00% | 0,06644 $ | 29/40 | +72,50% | +15,00% | 0,08043 $ | 14/29 | +48,28% | +21,05% | BASSA | 5,5 | 18,0 |
| -5,00% | 0,06644 $ | 29/40 | +72,50% | +20,00% | 0,08393 $ | 12/29 | +41,38% | +26,32% | BASSA | 5,5 | 20,0 |
| -8,00% | 0,06434 $ | 23/40 | +57,50% | +5,00% | 0,07344 $ | 13/23 | +56,52% | +14,13% | MEDIA | 5,9 | 13,7 |
| -8,00% | 0,06434 $ | 23/40 | +57,50% | +10,00% | 0,07693 $ | 13/23 | +56,52% | +19,57% | MEDIA | 5,9 | 16,3 |
| -8,00% | 0,06434 $ | 23/40 | +57,50% | +15,00% | 0,08043 $ | 9/23 | +39,13% | +25,00% | BASSA | 5,9 | 18,6 |
| -8,00% | 0,06434 $ | 23/40 | +57,50% | +20,00% | 0,08393 $ | 7/23 | +30,43% | +30,43% | DEBOLE | 5,9 | 21,6 |
| -10,00% | 0,06295 $ | 19/40 | +47,50% | +5,00% | 0,07344 $ | 9/19 | +47,37% | +16,67% | BASSA | 6,0 | 14,1 |
| -10,00% | 0,06295 $ | 19/40 | +47,50% | +10,00% | 0,07693 $ | 9/19 | +47,37% | +22,22% | BASSA | 6,0 | 17,8 |
| -10,00% | 0,06295 $ | 19/40 | +47,50% | +15,00% | 0,08043 $ | 6/19 | +31,58% | +27,78% | DEBOLE | 6,0 | 17,7 |
| -10,00% | 0,06295 $ | 19/40 | +47,50% | +20,00% | 0,08393 $ | 5/19 | +26,32% | +33,33% | DEBOLE | 6,0 | 22,0 |
| -15,00% | 0,05945 $ | 11/40 | +27,50% | +5,00% | 0,07344 $ | 1/11 | +9,09% | +23,53% | DEBOLE | 7,6 | 9,0 |
| -15,00% | 0,05945 $ | 11/40 | +27,50% | +10,00% | 0,07693 $ | 1/11 | +9,09% | +29,41% | DEBOLE | 7,6 | 10,0 |
| -15,00% | 0,05945 $ | 11/40 | +27,50% | +15,00% | 0,08043 $ | 1/11 | +9,09% | +35,29% | DEBOLE | 7,6 | 10,0 |
| -15,00% | 0,05945 $ | 11/40 | +27,50% | +20,00% | 0,08393 $ | 1/11 | +9,09% | +41,18% | DEBOLE | 7,6 | 27,0 |

## Tabella dump dopo spike

| Prima sale | Prezzo spike | Casi spike | % casi spike | Poi scarica a | Prezzo target | Casi scarico | % scarico | Movimento reale | Forza | Giorni spike | Giorni dump |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| +5,00% | 0,07344 $ | 31/40 | +77,50% | prezzo iniziale | 0,06994 $ | 21/31 | +67,74% | -4,76% | ALTA | 7,5 | 14,5 |
| +5,00% | 0,07344 $ | 31/40 | +77,50% | -5,00% | 0,06644 $ | 9/31 | +29,03% | -9,52% | DEBOLE | 7,5 | 12,4 |
| +5,00% | 0,07344 $ | 31/40 | +77,50% | -8,00% | 0,06434 $ | 6/31 | +19,35% | -12,38% | DEBOLE | 7,5 | 10,7 |
| +5,00% | 0,07344 $ | 31/40 | +77,50% | -10,00% | 0,06295 $ | 4/31 | +12,90% | -14,29% | DEBOLE | 7,5 | 9,0 |
| +5,00% | 0,07344 $ | 31/40 | +77,50% | -15,00% | 0,05945 $ | 1/31 | +3,23% | -19,05% | DEBOLE | 7,5 | 25,0 |
| +10,00% | 0,07693 $ | 31/40 | +77,50% | prezzo iniziale | 0,06994 $ | 15/31 | +48,39% | -9,09% | BASSA | 12,0 | 18,9 |
| +10,00% | 0,07693 $ | 31/40 | +77,50% | -5,00% | 0,06644 $ | 4/31 | +12,90% | -13,64% | DEBOLE | 12,0 | 18,8 |
| +10,00% | 0,07693 $ | 31/40 | +77,50% | -8,00% | 0,06434 $ | 2/31 | +6,45% | -16,36% | DEBOLE | 12,0 | 16,0 |
| +10,00% | 0,07693 $ | 31/40 | +77,50% | -10,00% | 0,06295 $ | 1/31 | +3,23% | -18,18% | DEBOLE | 12,0 | 11,0 |
| +10,00% | 0,07693 $ | 31/40 | +77,50% | -15,00% | 0,05945 $ | 1/31 | +3,23% | -22,73% | DEBOLE | 12,0 | 25,0 |
| +15,00% | 0,08043 $ | 25/40 | +62,50% | prezzo iniziale | 0,06994 $ | 3/25 | +12,00% | -13,04% | DEBOLE | 16,3 | 25,0 |
| +15,00% | 0,08043 $ | 25/40 | +62,50% | -5,00% | 0,06644 $ | 0/25 | 0,00% | -17,39% | DEBOLE | 16,3 | n/d |
| +15,00% | 0,08043 $ | 25/40 | +62,50% | -8,00% | 0,06434 $ | 0/25 | 0,00% | -20,00% | DEBOLE | 16,3 | n/d |
| +15,00% | 0,08043 $ | 25/40 | +62,50% | -10,00% | 0,06295 $ | 0/25 | 0,00% | -21,74% | DEBOLE | 16,3 | n/d |
| +15,00% | 0,08043 $ | 25/40 | +62,50% | -15,00% | 0,05945 $ | 0/25 | 0,00% | -26,09% | DEBOLE | 16,3 | n/d |
| +20,00% | 0,08393 $ | 22/40 | +55,00% | prezzo iniziale | 0,06994 $ | 1/22 | +4,55% | -16,67% | DEBOLE | 19,1 | 30,0 |
| +20,00% | 0,08393 $ | 22/40 | +55,00% | -5,00% | 0,06644 $ | 0/22 | 0,00% | -20,83% | DEBOLE | 19,1 | n/d |
| +20,00% | 0,08393 $ | 22/40 | +55,00% | -8,00% | 0,06434 $ | 0/22 | 0,00% | -23,33% | DEBOLE | 19,1 | n/d |
| +20,00% | 0,08393 $ | 22/40 | +55,00% | -10,00% | 0,06295 $ | 0/22 | 0,00% | -25,00% | DEBOLE | 19,1 | n/d |
| +20,00% | 0,08393 $ | 22/40 | +55,00% | -15,00% | 0,05945 $ | 0/22 | 0,00% | -29,17% | DEBOLE | 19,1 | n/d |

---
