# Antigravity Rules & Project Guidelines

These core guidelines apply strictly across all projects, workflows, and code updates.

## 1. Core Operating Principles (Mandatory)
1. **No Reverting Changes (Forward-Only Progress)**: Never revert, rollback, or erase previously completed changes and features unless explicitly requested. Always fix, improve, or build forward on top of existing code.
2. **App Language, UI & Code in English**: All application code, variables, comments, HTML, UI labels, buttons, modals, and screen text MUST strictly be in English.
3. **Marathi Conversation**: The conversational interface with the user MUST strictly remain in Marathi (मराठी संवाद).
4. **Immediate Git Push for Vercel Live Deployment**: After every successful code modification or feature addition, immediately stage (`git add .`), commit with a descriptive message (`git commit -m "..."`), and push to `origin main` so that Vercel automatically deploys the update live immediately.

## 2. Project Organization & Clean Workspace
- **Project Isolation**: Every project resides in its dedicated directory.
- **No Loose Files**: Never drop loose `.py`, `.txt`, `.html`, or temporary data files directly in root `scratch/`.
- **Target Verification**: Before modifying files, verify line numbers and exact contents to ensure safe application.

## 3. Completion Signal Rule
- **Last Line Requirement**: At the conclusion of every response where an action, update, or task is completed, always conclude on the very last line with:
  `Task is completed. ✅`
