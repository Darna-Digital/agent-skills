---
name: composable-functions-skill
description: Prepares boilerplate for clean, testable code
---

## What are composable functions?
The structure follows clean code principles with:

1. Interfaces defining dependencies and functions
2. Pure functions that depend on injected dependencies
3. Mocks for testing
4. Adapters (RSC/Hooks) that wire up real dependencies
5. Tests that validate behavior

## What I do

1. Look at the structure in .opencode/skill/composable-functions-skill/example
2. Read it to get context, understand the clean code patterns, DI, testing
3. Ask the user for the feature name
4. Generate boilerplate code for the relevant feature.
5. Location is in src/features
6. The files, interfaces and functions should follow the feature name specified by the user
7. Don't focus on implementing business logic yet, just generate a bare minimum boilerplate 
8. Finally, ask the user what type of adapter he wants to create.
9. Default options: RSC (react server components), React Hooks.
10. If user specifies something else like API, proxy-handler, etc. Look at the codebase for examples. If you can't find them, then come up with your own way to implement the adapter.

## How to use me

Call me in a chat, otherwise I won't load the context.
