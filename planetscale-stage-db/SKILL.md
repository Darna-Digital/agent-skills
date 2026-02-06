---
name: planetscale-stage-db
description: Connect to the PlanetScale staging database branch and execute SQL queries/mutations. Use when the user wants to query the staging database, run SQL against the staging environment, inspect staging data, or execute mutations on the staging PlanetScale branch.
---

## Workflow

1. Read `.env.stage-db` for connection credentials
2. Connect to the PlanetScale staging branch (MySQL)
3. Ask the user what queries or mutations to execute
4. Convert user requests to SQL and execute them against the database