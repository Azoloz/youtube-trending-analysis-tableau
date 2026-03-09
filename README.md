# YouTube Trending Analysis Dashboard (Tableau)

Interactive Tableau Public project to analyze historical YouTube trending videos by date, category, and region.

## Live Dashboard
[View on Tableau Public](https://public.tableau.com/app/profile/anuar.orlando.valdez.perez/viz/DashboarddetendenciasAnuar/Dashboard1)

## Project Objective
Analyze YouTube trending history to support advertising video planning decisions.

## Dataset
- `trending_by_time.csv`
- Fields:
  - `record_id`: primary key
  - `region`: country/region
  - `trending_date`: date and time when a video trended
  - `category_title`: video category
  - `videos_count`: number of trending videos

## Dashboard Scope
- Historical trends by day and category (absolute values)
- Historical trends by day and category (percentage share)
- Event distribution by country/region
- Category-country correspondence table

## Business Questions Answered
- Which video categories trended most frequently?
- How were trending videos distributed across regions?
- Which categories were especially popular in the United States, and how did they differ from other regions?

## Key Findings
- Trending behavior is not homogeneous across regions; category popularity varies significantly by country.
- U.S. category distribution differs from several non-U.S. regions, confirming the need for localized advertising strategies.
- The combination of absolute and percentage trend views helps distinguish high-volume categories from high-share categories.

## Screenshots
![Dashboard Preview](https://public.tableau.com/static/images/Da/DashboarddetendenciasAnuar/Dashboard1/1.png)

If the preview image does not render in your browser, use the live dashboard link above.

## How to Use
1. Open the `Live Dashboard` link.
2. Set the global date/time filter to the period you want to analyze.
3. Use the country filter to compare one region against others.
4. Read `Historical trends` for absolute volumes and `Historical trends, %` for category share.
5. Use the country distribution chart and category-country table to identify localization opportunities.

## Resume Bullet Version
**YouTube Trending Dashboard (Tableau Public)** | **TripleTen Data Analyst Bootcamp (2026)**

- Designed and published an interactive Tableau Public dashboard to analyze historical YouTube trending behavior by date, category, and region, resulting in a repeatable daily monitoring workflow for marketing planning.
- Built absolute and percentage trend views plus country-level distribution analysis, resulting in clear comparisons of U.S. category performance versus other regions through global date/time and country filters.
- Standardized insight delivery for non-technical stakeholders, reducing manual weekly reporting effort and improving consistency in trend interpretation.

**Technological skills used:** Tableau Public, Data Visualization, SQL, Exploratory Data Analysis (EDA), Git/GitHub

## Resume Bullet Version - ES
**YouTube Trending Dashboard (Tableau Public)** | **TripleTen Data Analyst Bootcamp (2026)**

- Disene y publique un dashboard interactivo en Tableau Public para analizar tendencias historicas de YouTube por fecha, categoria y region, lo que resulto en un flujo de monitoreo diario replicable para planeacion de marketing.
- Construi vistas de tendencias absolutas y porcentuales, junto con analisis por pais, lo que permitio comparar claramente el desempeno de categorias en EE. UU. frente a otras regiones mediante filtros globales de fecha/hora y pais.
- Estandarice la entrega de insights para stakeholders no tecnicos, reduciendo el esfuerzo manual semanal de reporte y mejorando la consistencia del analisis.

**Habilidades tecnologicas utilizadas:** Tableau Public, Visualizacion de Datos, SQL, Analisis Exploratorio de Datos (EDA), Git/GitHub

## Tools
- Tableau Public
- SQL (data preparation context)
- Data visualization

## Repository Structure
- `trending_by_time.csv`: source dataset used to build the dashboard
- `README.md`: project documentation

## Author
Project developed as part of the TripleTen Data Analyst Bootcamp (2026).
