---
name: qa-plan-skill
description: Generate a BDD-style QA test plan as a CSV file based on current branch changes. Use when the user wants to create a QA plan, prepare test scenarios for a feature, generate BDD test cases, or document manual testing steps for a task.
---

## Workflow

1. Check current branch commits to identify what changed
2. Inspect the affected components, templates, pages, and elements in the codebase
3. Extract URLs, user behaviors, buttons, links, and forms that need testing
4. Determine if authentication is required for testing
5. Derive the file name from the current git branch task number and name
6. Generate a CSV file in this skill's `plans/` folder (locate it next to this SKILL.md) with BDD columns:
   `Scenario | Given | When | Then | Status`
