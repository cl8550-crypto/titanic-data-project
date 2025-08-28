# Titanic Data Project

## Project Summary
We will predict passenger survival on the Titanic using basic demographic and travel information. This small project demonstrates a reproducible data pipeline—from raw data to cleaned data—so it can be adapted to real-world safety/risk questions.

## Stakeholder Persona
Primary stakeholder: a shipping-company safety officer who wants to identify higher-risk passenger groups to guide safety planning, evacuation procedures, and resource allocation.

## Repo Structure
- /data/ — all datasets
- /data/raw/ — raw data (downloaded/ingested)
- /data/processed/ — saved processed datasets
- /notebooks/ — demo/analysis notebooks
- /src/ — Python scripts (utils, cleaning)
- /docs/ — documentation and memos

## Preprocessing Assumptions
- Missing Age filled with dataset median.
- Sex encoded as 0/1 for simple downstream modeling.
- Cleaned dataset saved to `data/processed/titanic_clean.csv`.
