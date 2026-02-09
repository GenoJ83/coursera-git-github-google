# What is a Repository?

- Summary: Definition and role of a Git repository.
- Definition: A repository is a folder tracked by Git that stores the project and its history.
- Contents: Working files, commits, branches, and the internal `.git` metadata.
- Common commands:
  - `ls -a` (or `dir /a` on Windows) to see `.git`
  - `git log` to view commit history
  - `git remote` and `git push`/`git pull` when linked to a remote (e.g., GitHub)
- Tip: Treat the repository as the source of truth—use branches for features and merge when ready.