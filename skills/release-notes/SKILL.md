---
name: release-notes
description: >
  Turn the commits since the last tag into short release notes,
  grouped by what a user notices.
---

# Release notes

Run `git log --oneline <last-tag>..HEAD`. Group the changes under "New", "Better" and "Fixed",
one line each, in the words a user would use. Leave out internal refactors.
