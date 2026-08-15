# Power BI Analytics Portfolio

This repository contains two Microsoft Power BI dashboard projects.

## Projects

| Project | Power BI file | Location |
| --- | --- | --- |
| Digital Market Analytics for Mercedes-Benz | `Mercedes_Benz_Digital_Market_Analytics.pbix` | `projects/mercedes-benz-digital-market-analytics/` |
| NVH Analysis Dashboard | `NVH_Analysis_Dashboard.pbix` | `projects/nvh-analysis-dashboard/` |

## Repository structure

```text
power-bi-analytics-portfolio/
|-- projects/
|   |-- mercedes-benz-digital-market-analytics/
|   |   |-- Mercedes_Benz_Digital_Market_Analytics.pbix
|   |   `-- README.md
|   `-- nvh-analysis-dashboard/
|       |-- NVH_Analysis_Dashboard.pbix
|       `-- README.md
|-- .gitattributes
|-- .gitignore
`-- README.md
```

## Opening the dashboards

1. Install Microsoft Power BI Desktop.
2. Download or clone this repository.
3. Open the required `.pbix` file from its project folder.
4. Refresh its data sources only when you have the required access and credentials.

## Version-control notes

Power BI `.pbix` files are binary, so Git cannot show meaningful line-by-line diffs or merge concurrent edits. Coordinate dashboard edits and avoid modifying the same file on multiple branches at once. For source-level version control in future work, consider converting each dashboard to the Power BI Project (`.pbip`) format.

## Data and access

This repository is public. Before replacing or updating a `.pbix` file, verify that its imported data, connection details, and business logic are approved for public distribution. Never commit credentials or other secrets.
