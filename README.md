# YouTube Trending Analysis Dashboard (Tableau)

Interactive Tableau Public project to analyze historical YouTube trending videos by date, category, and region.

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

## Tools
- Tableau Public
- SQL (data preparation context)
- Data visualization

## Repository Structure
- `trending_by_time.csv`: source dataset used to build the dashboard
- `README.md`: project documentation

## Author
Project developed as part of the TripleTen Data Analyst Bootcamp (2026).
