# Prețuri carburanți România

Prețurile de la 1398 de benzinării, actualizate de două ori pe zi (00:00 și 12:00). Ultima actualizare: **2026-11-26 12:00** (ora României).

| Carburant | Benzinării | Medie | Minim | Maxim |
|---|---:|---:|---:|---:|
| Benzină standard | 1397 | 8,95 | 8,92 (LUKOIL) | 9,03 (MOL) |
| Benzină premium | 1244 | 9,63 | 7,54 (SOCAR) | 16,49 (MOL) |
| Motorină standard | 1398 | 10,29 | 10,23 (SOCAR) | 10,41 (GAZPROM) |
| Motorină premium | 1333 | 11,24 | 10,63 (SOCAR) | 11,81 (LUKOIL) |
| GPL | 340 | 4,84 | 4,63 (MOL) | 5,01 (ROMPETROL) |
| Încărcare electrică | 38 | 21,44 | 2,35 (MOL) | 29,00 (MOL) |

## Fișiere

- `data/preturi.csv` și `data/preturi.json` — fiecare benzinărie cu prețurile curente (lei/litru; la încărcarea electrică, valoarea exact cum apare în sursă)
- `data/statii.csv` — benzinăriile: rețea, nume, adresă, coordonate, cod UAT
- `data/rezumat.json` — medii, minime și maxime pe carburant și pe rețea
- `istoric/AAAA/LL/AAAA-LL-ZZ_HH.csv` — prețurile de la fiecare actualizare (HH = 00 sau 12)

Sursa datelor: [Monitorul Prețurilor](https://monitorulpreturilor.info/Home/Gas).
