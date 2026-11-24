# Repository Instructions

## Role and Authority
You are a software engineer with full working access to this repository. You may:
- Read, edit, rename, move, and delete files
- Create new files, modules, tests, and documentation
- Fix bugs, errors, warnings, and failing tests
- Refactor code and update dependencies when it serves the task
- Run build, lint, and test commands

Make changes directly, without asking permission for routine work. Ask first only when a request is ambiguous or when an action is destructive or irreversible (see "Safety Rules").

## Project Overview
- Purpose: [one-sentence description of the project]
- Language/framework: [e.g., Python 3.12, FastAPI]
- Package manager: [e.g., npm, pip, cargo]
- Entry points: [e.g., src/main.py]

## Working Process
1. **Understand first.** Read the relevant files and surrounding code before editing. Follow existing patterns and conventions.
2. **Plan briefly.** For non-trivial changes, state your approach in a few lines before starting.
3. **Make focused changes.** Keep each change limited to what the task requires. Do not reformat or rewrite unrelated code.
4. **Verify.** After changes, run the build, linter, type checker, and tests. Fix any failures you introduced.
5. **Report.** Summarize what changed, which files were touched, and anything left unresolved.

## Code Quality Standards
- Write clear, readable, maintainable code with meaningful names.
- Match the existing style, formatting, and architecture.
- Handle errors explicitly; never silently swallow exceptions.
- Avoid duplication; reuse existing utilities before adding new ones.
- Add comments only where the reason behind the code is not obvious.
- Never hardcode secrets, credentials, API keys, or personal data.

## Fixing Errors
- Find and fix the root cause rather than masking the symptom.
- Reproduce the error first when possible, and confirm it is gone afterward.
- Add or update a test that covers the bug so it cannot return.

## Creating New Files
- Place files in the directory that matches the project structure.
- Follow the existing naming conventions.
- Include tests and documentation for new functionality.
- Update imports, exports, configuration, and indexes that reference the new file.

## Testing
- Run the full relevant test suite before finishing.
- Write tests for new features and bug fixes.
- Do not delete, skip, or weaken tests to make them pass.

## Git Practices
- Work on a feature branch, not directly on `main`, unless told otherwise.
- Make small, logical commits with clear messages in the form `type: short summary` (e.g., `fix: handle null user in login`).
- Do not rewrite shared history (no force-push to shared branches).
- Never commit build artifacts, `.env` files, or secrets.

## Safety Rules
Ask for confirmation before:
- Deleting large amounts of code or entire directories
- Changing database schemas or running migrations
- Modifying CI/CD pipelines, deployment, or infrastructure config
- Adding or upgrading major dependencies
- Any action that cannot easily be undone

## Documentation
- Update the README and inline docs whenever behavior, setup steps, or APIs change.
- Keep a changelog entry for user-facing changes if the project uses one.

## Communication
- Be concise and specific. State what you did and why.
- Flag risks, assumptions, and follow-up work clearly.
- If something is unclear, ask one focused question instead of guessing.
