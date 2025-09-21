# Pomurje vs. ostale regije — Zdrava leta življenja (HLY) in determinante
[English below](#english)

Analiza razlik v zdravih letih življenja (HLY) med slovenskimi regijami in povezav z determinantami zdravja.
Glavne ugotovitve: **višja delovna aktivnost (+)** in **višji ITM (−)** najmočneje pojasnjujeta razlike v HLY.

## Struktura repozitorija
- `prekmurje_determinante.Rmd` – reproducibilno poročilo (koda + grafi).
- `data/tableau/` – izvozi CSV za Tableau (radar, observed vs predicted …).
- `data/processed/` –  master CSV za analizo.

## Kako pognati
1. Odpri projekt v RStudiu in `prekmurje_determinante.Rmd`.
2. Dodaj `master_regijski_kazalniki_chat.csv` v `data/processed/`.
3. **Knit** → HTML.

Viri: SURS, NIJZ; lastni izračuni. Licenca kode: MIT.

### Live story (Tableau)
(https://public.tableau.com/views/Book1Pomurjevs_ostaleregijeZdravaletaivljenjaHLYindeterminante/Story1?:showVizHome=no&:toolbar=top)


---

## English

Analysis of differences in **Healthy Life Years (HLY)** across Slovenian regions and their association with health determinants.
Key finding: **employment/active workforce (+)** and **BMI/overweight (−)** explain most variation in HLY.

### Repository layout
- `prekmurje_determinante.Rmd` – reproducible report (code + figures).
- `data/tableau/` – CSV exports for Tableau.
- `data/processed/` –  master CSV.

### How to run
1. Open the project in RStudio and the Rmd file.
2. Place `master_regijski_kazalniki_chat.csv` into `data/processed/`.
3. Click **Knit** → HTML.

Sources: SORS, NIJZ; own calculations. License: MIT.

### Live story (Tableau)
(https://public.tableau.com/views/Book1Pomurjevs_ostaleregijeZdravaletaivljenjaHLYindeterminante/Story1?:showVizHome=no&:toolbar=top)


