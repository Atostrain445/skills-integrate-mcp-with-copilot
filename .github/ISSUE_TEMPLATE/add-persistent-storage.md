---
name: "Add persistent storage and User model"
about: "Replace in-memory activity storage with a proper database; create Activity and User models, migrations and tests."
title: "Add persistent storage and User model"
labels: ""
assignees: ""
---

Replace the in-memory activity storage with a database-backed model.

Tasks:
<<<<<<< HEAD
- Create `Activity` and `User` models
=======
- Create Activity and User models
>>>>>>> 0e979fc43bcb794b49fbac437319c1081235150b
- Add migrations and database configuration
- Update endpoints to use the DB instead of the in-memory dict
- Add basic tests for persistence and migrations

Related issue: https://github.com/Atostrain445/skills-integrate-mcp-with-copilot/issues/8
