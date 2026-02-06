---
name: seo-spider-skill
description: Analyze SEO spider crawl reports, prioritize issues, and generate technical fix suggestions. Use when the user wants to review SEO audit results, analyze crawl issues (canonicals, meta tags, response codes, headings, images, URLs), or get technical recommendations for fixing SEO problems.
---

## Workflow

1. Locate the `issues_reports/` folder next to this SKILL.md (create if missing)
2. Read `issues_overview_report.csv` from that folder
3. List issues sorted by severity (high to low)
4. Ask the user which issue to analyze
5. Read the relevant CSV file from the `issues_reports/` folder
6. Search the project's routing structure (e.g. `src/app`) to locate the affected pages
7. Generate technical suggestions to fix the issue
8. Write suggestions to the `seo-suggestions/` folder next to this SKILL.md as `<suggestion-name>.md`
