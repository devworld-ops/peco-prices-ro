# Prețuri carburanți România

Prețurile de la 1396 de benzinării, actualizate de două ori pe zi (00:00 și 12:00). Ultima actualizare: **2026-11-23 12:00** (ora României).

| Carburant | Benzinării | Medie | Minim | Maxim |
|---|---:|---:|---:|---:|
| Benzină standard | 1392 | 9,06 | 8,98 (PETROM) | 9,16 (MOL) |
| Benzină premium | 1241 | 9,71 | 7,54 (SOCAR) | 16,49 (MOL) |
| Motorină standard | 1393 | 10,51 | 10,43 (PETROM) | 10,63 (MOL) |
| Motorină premium | 1330 | 11,41 | 10,88 (SOCAR) | 11,81 (LUKOIL) |
| GPL | 340 | 4,84 | 4,63 (MOL) | 5,01 (ROMPETROL) |
| Încărcare electrică | 38 | 21,44 | 2,35 (MOL) | 29,00 (MOL) |

## Fișiere

- `data/preturi.csv` și `data/preturi.json` — fiecare benzinărie cu prețurile curente (lei/litru; la încărcarea electrică, valoarea exact cum apare în sursă)
- `data/statii.csv` — benzinăriile: rețea, nume, adresă, coordonate, cod UAT
- `data/rezumat.json` — medii, minime și maxime pe carburant și pe rețea
- `istoric/AAAA/LL/AAAA-LL-ZZ_HH.csv` — prețurile de la fiecare actualizare (HH = 00 sau 12)

Sursa datelor: [Monitorul Prețurilor](https://monitorulpreturilor.info/Home/Gas).
