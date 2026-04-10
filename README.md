# Portfolio Power BI — Rafał Wyszomierski

Junior Data Analyst | Doktor ekonomii | 6 lat w branży OZE

## Dashboardy

### 1. Emisje CO2 2000-2021
- 3 strony: emisje według źródeł, per capita, PKB vs emisje
- Narzędzia: Power BI, DAX, Power Query
- Dataset: Our World in Data

### 2. Globalne trendy energii i emisji CO2
- Analiza trendów energetycznych
- Narzędzia: Power BI, DAX

### 3. Rynek samochodów elektrycznych 2023
- Analiza rynku EV
- Narzędzia: Power BI, DAX

## 4. OZE vs Makroekonomia — Polska na tle UE-27 | 2000–2025

<img width="800" alt="OZE vs Makroekonomia Dashboard" src="https://github.com/user-attachments/assets/3d795f63-3cb6-4c5f-8670-cc85f9ab005b" />
<img width="800" alt="OZE vs Makroekonomia Dashboard" src="https://github.com/user-attachments/assets/24c87eaa-d165-4eaa-b701-b5e405417108" />
<img width="800" alt="OZE vs Makroekonomia Dashboard" src="https://github.com/user-attachments/assets/ce50e6f9-7db9-4580-a3a6-52ba7b3b889e" />


🔗 [Zobacz w Power BI Service](https://app.powerbi.com/groups/me/reports/4e12cc70-6934-4ddf-8770-2a7669cdca52/65e44764170cc11b5e19?experience=power-bi)  *(wymaga konta Power BI)*

Analiza porównawcza transformacji energetycznej i wskaźników makroekonomicznych 
dla 27 krajów UE w latach 2000–2025.

**Kluczowe wnioski:**
- 🇵🇱 Polska #23 z 27 krajów UE pod względem OZE (17,8% vs średnia UE 25,2%)
- ⚡ Odwrócenie trendu — od 2023 r. energia dla przemysłu w PL droższa niż średnia UE
- 📉 Korelacje OZE bliskie zeru — transformacja bardziej polityczna niż ekonomiczna

**Stack:** Power BI · DAX · Power Query · ETL · Star Schema · MCP + Claude AI  
**Dane:** Eurostat (6 zbiorów TSV) | 27 krajów | 2000–2025

## Jak otworzyć?
Pobierz plik .pbix i otwórz w Power BI Desktop (darmowy).

## 5. Prognoza cen energii — Polska vs UE-27 (2025–2030)

<img width="1412" height="772" alt="image" src="https://github.com/user-attachments/assets/e79f83f7-7e4c-479e-8920-3c6bea0509a7" />
<img width="1422" height="791" alt="image" src="https://github.com/user-attachments/assets/84145836-0d35-42d1-88ee-4fc07642f651" />
<img width="1416" height="793" alt="image" src="https://github.com/user-attachments/assets/17c5213c-3b54-4d72-a87a-cfa390fbc8ca" />

Dashboard w Power BI z prognozami cen energii elektrycznej
dla Polski i UE-27 do 2030 roku. Model Prophet (Meta)
dla cen gospodarstw domowych i przemysłu.

## Kluczowe wnioski
Polska utrzyma niższe ceny dla gospodarstw domowych
od średniej UE przez cały horyzont prognozy.
Polska nie odzyska przewagi cenowej dla przemysłu przed 2030.
Punkt przełomu 2023 — po raz pierwszy od 15 lat ceny
dla przemysłu w Polsce przekroczyły średnią UE-27.

## Dane
Eurostat | nrg_pc_204, nrg_pc_205 | PL i EU27_2020 | 2007–2025

## MAPE
Gosp. domowe UE    18,4%
Przemysł UE        22,1%
Gosp. domowe PL    23,6%
Przemysł PL        50,5%

Wysoki MAPE wynika z kryzysu energetycznego 2022
i inwazji Rosji na Ukrainę — nie z błędu modelu.

## Stack
Power BI, Python (Prophet), DAX, Power Query, MCP + Claude AI

## Autor
Rafał Wyszomierski | linkedin.com/in/rafal-wyszomierski
