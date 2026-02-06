---
name: task-analysis-skill
description: Analyze a task (from Slack messages, Jira tickets, screenshots, or verbal descriptions) in the context of the codebase and produce an implementation plan. Use when the user wants to break down a task, plan an implementation, analyze how a feature should be built, or create a technical analysis document for a ticket.
---

## Workflow

1. Ask the user for task context (Slack messages, Jira ticket info, screenshots, etc.)
2. Understand the intent of the task
3. Analyze the codebase for relevant information
4. Analyze existing features for code structure and testability patterns
5. Determine whether to adjust an existing feature or create a new one
6. Write an implementation plan as a markdown file in this skill's `analyses/` folder (locate it next to this SKILL.md)
7. If the branch includes a task slug (e.g. `task/HNV3-1579-fe-missing-order-tracking-id`), prefix the analysis filename with that task number
