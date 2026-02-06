---
name: planetscale-dev-db
description: Connect to the PlanetScale development database branch and execute SQL queries/mutations. Use when the user wants to query the dev database, run SQL against the development environment, inspect dev data, or execute mutations on the development PlanetScale branch.
---

## Workflow

1. Read `.env.dev-db` for connection credentials
2. Connect to the PlanetScale development branch (MySQL)
3. Ask the user what queries or mutations to execute
4. Convert user requests to SQL and execute them against the database