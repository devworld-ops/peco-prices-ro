# Prețuri carburanți România

Prețurile de la 1399 de benzinării, actualizate de două ori pe zi (00:00 și 12:00). Ultima actualizare: **2026-11-07 00:00** (ora României).

| Carburant | Benzinării | Medie | Minim | Maxim |
|---|---:|---:|---:|---:|
| Benzină standard | 1398 | 9,90 | 9,85 (SOCAR) | 10,17 (GAZPROM) |
| Benzină premium | 1245 | 10,49 | 7,54 (SOCAR) | 16,49 (MOL) |
| Motorină standard | 1399 | 10,89 | 10,83 (SOCAR) | 10,99 (GAZPROM) |
| Motorină premium | 1334 | 11,75 | 10,97 (ROMPETROL) | 11,88 (MOL) |
| GPL | 339 | 4,73 | 4,54 (MOL) | 4,99 (MOL) |
| Încărcare electrică | 38 | 21,44 | 2,35 (MOL) | 29,00 (MOL) |

## Fișiere

- `data/preturi.csv` și `data/preturi.json` — fiecare benzinărie cu prețurile curente (lei/litru; la încărcarea electrică, valoarea exact cum apare în sursă)
- `data/statii.csv` — benzinăriile: rețea, nume, adresă, coordonate, cod UAT
- `data/rezumat.json` — medii, minime și maxime pe carburant și pe rețea
- `istoric/AAAA/LL/AAAA-LL-ZZ_HH.csv` — prețurile de la fiecare actualizare (HH = 00 sau 12)

Sursa datelor: [Monitorul Prețurilor](https://monitorulpreturilor.info/Home/Gas).
