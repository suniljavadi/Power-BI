# Power BI Analytics Portfolio

**Status: Learning and portfolio collection**

A collection of Power BI reports, AdventureWorks-based exercises, dashboard documentation, supporting data files, screenshots, and assignment packages. The repository demonstrates business-intelligence practice and report development; it is not a single automated application or deployable service.

## What This Repository Contains

- Power BI Desktop reports in `.pbix` format
- AdventureWorks sales analysis materials
- Power Query data-shaping exercises
- Sales dashboard and reporting exercises
- Games sales dashboard material
- University applications and SuperStore report examples
- Supporting Excel, SQL, DOCX, PDF, image, backup, and ZIP files

The original assignment archives are retained alongside extracted folders so the source packages remain available.

## Portfolio Areas

| Folder | Focus | Evidence |
| --- | --- | --- |
| `adventureworks-sales-assignment/` | AdventureWorks sales reporting | Report package and supporting files |
| `adventureworks-data-modeling-assignment/` | Data-modeling exercise | AdventureWorks package files |
| `adventureworks-sales-dashboard/` | Sales dashboard workflow | PBIX, Excel, SQL, and database backup |
| `adventureworks-sales-package/` | AdventureWorks report package | PBIX report and archive |
| `power-query-data-shaping-assignment/` | Power Query and data shaping | PBIX files and assignment package |
| `sales-dashboard-reporting-assignment/` | Sales reporting and documentation | PBIX/package, PDFs, and DOCX |
| `games-sales-dashboard/` | Games sales dashboard | PBIX report and PDF report |
| `power-bi-data-modeling-assignment/` | Power BI modeling exercise | PBIX report |
| `power-bi-project-2/` | Supporting dashboard examples | PBIX files and dashboard images |

## Technology Scope

| Area | Repository evidence |
| --- | --- |
| BI tool | Power BI Desktop report files (`.pbix`) |
| Data modeling | AdventureWorks and other sample report assets |
| Data preparation | Power Query-oriented assignment materials |
| Data sources | Excel, SQL, CSV-adjacent package content, and an AdventureWorks backup |
| Documentation | PDF and DOCX report/support materials |
| Visual review | PNG/JPG dashboard images |

The repository does not contain a Python application, API, CI workflow, automated test suite, or command-line build pipeline.

## How To Explore

### Prerequisites

- Windows with Power BI Desktop for `.pbix` files
- Access to any referenced sample data or database backup when a report requests it
- SQL Server tools only for inspecting or restoring the included SQL/backup materials

### Open A Report

1. Clone the repository.
2. Open a selected `.pbix` file in Power BI Desktop.
3. Review Power Query transformations, relationships, measures, report pages, filters, and visuals.
4. If a data source is unavailable, use the report’s existing documentation and sample files to identify the expected source.

Example locations:

```text
adventureworks-sales-dashboard/adventureworks-sales-dashboard-files/adventureworks-sales-dashboard.pbix
games-sales-dashboard/games-sales-dashboard.pbix
power-bi-data-modeling-assignment/power-bi-data-modeling-assignment.pbix
power-bi-project-2/SuperStorep2.pbix
```

## Data and Supporting Files

The repository includes sample-oriented assets such as Excel workbooks, a SQL lab script, an AdventureWorks `.bak` backup, screenshots, reports, and nested ZIP packages. These files are retained as learning materials. No production data, client data, or verified business-impact metrics are claimed.

## Architecture At A Glance

```mermaid
flowchart LR
    S[Sample files and database assets] --> P[Power Query preparation]
    P --> M[Power BI data model]
    M --> D[DAX measures and KPIs]
    D --> R[Report pages and dashboards]
    R --> E[PDF, DOCX, or image documentation]
```

This is a conceptual view of the report workflow represented by the repository assets. The repository does not include an automated refresh or deployment pipeline.

## Validation

There is no command-line test suite for PBIX report behavior. Validation requires Power BI Desktop and should be performed manually for each selected report:

- Confirm the report opens without missing-file prompts.
- Check Power Query refresh steps against the available sample sources.
- Review relationships and model fields.
- Inspect DAX measures and visual filters.
- Compare report pages with the included PDF/image documentation where available.

Automated validation, refresh testing, and measure-level regression tests are not currently implemented.

## Limitations

- PBIX files are binary and cannot be meaningfully reviewed from a plain-text terminal.
- Data-source paths and credentials are environment-specific.
- Report refresh behavior depends on Power BI Desktop and available sample data.
- Assignment packages contain nested archives and duplicated learning materials.
- No deployment target, Power BI Service workspace, gateway configuration, or CI/CD workflow is included.

## Future Enhancements

- Add a report catalog with screenshots, business questions, data sources, and key measures.
- Document the data model and important DAX measures for each flagship report.
- Add sanitized sample data and refresh instructions where redistribution is appropriate.
- Add a Power BI Service deployment guide only when an actual workspace and deployment process exist.

## Engineering Highlights

- Business-facing report and dashboard organization
- AdventureWorks sales analysis and modeling exercises
- Power Query/data-shaping practice
- Supporting SQL, Excel, documentation, and database artifacts
- Preservation of original assignment packages alongside browsable extracted assets

## Interview Topics

- How would you design a star schema for AdventureWorks sales reporting?
- Which transformations belong in Power Query versus DAX?
- How would you validate a Power BI model after a source-schema change?
- How would you improve report refresh performance?
- How would you document measures and business definitions for analysts?
- How would you introduce deployment and refresh governance in Power BI Service?

## Author

**Sunil Javadi**

- [GitHub](https://github.com/suniljavadi)
- [Portfolio](https://github.com/suniljavadi/sunil-portfolio)
- [LinkedIn](https://www.linkedin.com/in/sunil-javadi/)
