# AGENTS.md — Project Contract

## Mission
Build and maintain the Pramuka extracurricular management website as a modern, responsive front-end prototype using React + Vite and local dummy data.

## Source of Truth
Read these files before implementing:
1. `docs/PRD.md`
2. `docs/UI-GUIDELINE.md`
3. `docs/IMPLEMENTATION_PLAN.md`

If instructions conflict, stop and ask the project owner. Do not silently expand scope.

## Hard Constraints
- Front-end UI only.
- React + Vite.
- Use local dummy data.
- No backend, API, database, external authentication, or production persistence.
- No feature outside the approved PRD.
- Do not claim demo login, CRUD, PDF export, or uploads are production-ready.
- Keep interface language Indonesian.
- Preserve the yellow, green, gray, white, and black brand palette.

## Working Rules
- Inspect existing files before changing them.
- Prefer small, focused changes.
- Reuse components and design tokens.
- Keep mock data in a dedicated module when practical.
- All primary buttons must work or clearly state why the action is unavailable.
- Confirm destructive actions.
- Include loading/empty/error-like UI states when appropriate for a demo.
- Keep keyboard focus visible and form controls labeled.
- Avoid unnecessary dependencies.
- Do not overwrite user work without asking.
- Never add secrets, credentials, or real personal data.

## Change Control
Before adding a feature or changing stack/scope, explain:
1. What needs to change.
2. Why it is needed.
3. Which SOT files are affected.
Wait for explicit approval.

## Verification
After each meaningful change:
- Run the available build/check command.
- Verify main navigation and demo role flows.
- Check desktop and mobile layouts.
- Report what was tested and what remains unverified.
Do not claim tests passed unless they were actually run.

## Completion Report
Summarize files changed, user-visible behavior, verification results, limitations, and any decision needed from the project owner.
