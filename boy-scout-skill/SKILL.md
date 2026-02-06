---
name: boy-scout-skill
description: Review and improve an existing task analysis plan by applying boy-scout principles (leave code better than you found it). Use when the user wants to improve an implementation plan, review an analysis for quality, suggest security/performance/UX improvements to a planned change, or refine an existing task-analysis-skill output.
---

## Workflow

1. Ask the user for the analysis name
2. Search the codebase for the task-analysis-skill's analyses folder and read the specified analysis
3. Read through the files in the codebase mentioned in the analysis for additional context
4. Ask the user if they have their own insights or concerns about the analysis
5. Apply the improvement rules below
6. Create a copy named `[existing-analysis-name]-improved` in the same folder as the original analysis

## Improvement Rules

1. Understand the business case of the project
2. Suggest improvements to the analysis under consideration
3. Identify what could be done better in the approach
4. Propose code improvements for long-term maintainability
5. Flag security and performance issues that can be addressed alongside the planned changes
6. Suggest product improvements for end users
7. Identify UX issues that can be resolved
