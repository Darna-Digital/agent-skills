---
name: local-redis-skill
description: Connect to and execute commands against a local Docker-based Redis instance. Use when the user wants to run Redis commands, inspect Redis keys/values, debug Redis data, or interact with the local Redis container.
---

## Workflow

1. Read `.redis.local` for the Redis connection URL
2. Connect to Redis via Docker
3. Ask the user what Redis commands to execute
4. Execute the requested commands and return results
