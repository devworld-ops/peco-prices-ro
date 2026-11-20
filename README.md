# Prețuri carburanți România

Prețurile de la 1399 de benzinării, actualizate de două ori pe zi (00:00 și 12:00). Ultima actualizare: **2026-11-20 12:00** (ora României).

| Carburant | Benzinării | Medie | Minim | Maxim |
|---|---:|---:|---:|---:|
| Benzină standard | 1398 | 9,16 | 9,05 (PETROM) | 9,30 (GAZPROM) |
| Benzină premium | 1245 | 9,77 | 7,54 (SOCAR) | 16,49 (MOL) |
| Motorină standard | 1399 | 10,59 | 10,53 (SOCAR) | 10,68 (GAZPROM) |
| Motorină premium | 1334 | 11,44 | 10,93 (SOCAR) | 11,81 (LUKOIL) |
| GPL | 340 | 4,84 | 4,59 (SOCAR) | 5,01 (ROMPETROL) |
| Încărcare electrică | 38 | 21,44 | 2,35 (MOL) | 29,00 (MOL) |

## Fișiere

- `data/preturi.csv` și `data/preturi.json` — fiecare benzinărie cu prețurile curente (lei/litru; la încărcarea electrică, valoarea exact cum apare în sursă)
- `data/statii.csv` — benzinăriile: rețea, nume, adresă, coordonate, cod UAT
- `data/rezumat.json` — medii, minime și maxime pe carburant și pe rețea
- `istoric/AAAA/LL/AAAA-LL-ZZ_HH.csv` — prețurile de la fiecare actualizare (HH = 00 sau 12)

Sursa datelor: [Monitorul Prețurilor](https://monitorulpreturilor.info/Home/Gas).
