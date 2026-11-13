# Prețuri carburanți România

Prețurile de la 1399 de benzinării, actualizate de două ori pe zi (00:00 și 12:00). Ultima actualizare: **2026-11-14 00:00** (ora României).

| Carburant | Benzinării | Medie | Minim | Maxim |
|---|---:|---:|---:|---:|
| Benzină standard | 1398 | 9,54 | 9,46 (SOCAR) | 9,84 (GAZPROM) |
| Benzină premium | 1245 | 10,14 | 7,54 (SOCAR) | 16,49 (MOL) |
| Motorină standard | 1399 | 10,71 | 10,64 (SOCAR) | 10,87 (GAZPROM) |
| Motorină premium | 1334 | 11,57 | 11,04 (SOCAR) | 11,81 (LUKOIL) |
| GPL | 340 | 4,78 | 4,59 (MOL) | 5,01 (ROMPETROL) |
| Încărcare electrică | 38 | 21,44 | 2,35 (MOL) | 29,00 (MOL) |

## Fișiere

- `data/preturi.csv` și `data/preturi.json` — fiecare benzinărie cu prețurile curente (lei/litru; la încărcarea electrică, valoarea exact cum apare în sursă)
- `data/statii.csv` — benzinăriile: rețea, nume, adresă, coordonate, cod UAT
- `data/rezumat.json` — medii, minime și maxime pe carburant și pe rețea
- `istoric/AAAA/LL/AAAA-LL-ZZ_HH.csv` — prețurile de la fiecare actualizare (HH = 00 sau 12)

Sursa datelor: [Monitorul Prețurilor](https://monitorulpreturilor.info/Home/Gas).
