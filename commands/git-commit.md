---
description: Git commit with auto-generated conventional commits message
agent: build
---

Please help me complete git commit:

1. Run `git status` to see current changes
2. Run `git add -A` to stage all modified files
3. Run `git diff --cached` to see staged changes
4. Analyze the changes and generate a commit message following the Conventional Commits spec:
   Format: <type>(<scope>): <subject>
   - type: feat, fix, docs, style, refactor, test, chore
   - scope: optional, describes what the change affects
   - subject: short description in English (imperative mood, lowercase, no period at end)
   
   Examples:
   - `feat: add user login functionality`
   - `fix: resolve button click handler not firing`
   - `docs: update installation instructions`
   - `style: format code with prettier`
   - `refactor: simplify authentication logic`
   - `test: add unit tests for user service`
   - `chore: update dependencies`
6. Use the question tool to confirm the commit message with the user
7. If confirmed, run `git commit -m "your commit message"` to complete the commit
8. If rejected, tell the user they can modify and run the command again
