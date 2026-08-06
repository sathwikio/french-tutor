# French Tutor

An agent-native, repository-backed French tutor for daily study and TEF Canada preparation.

## Start a session

Open this repository in Codex CLI, OpenCode, or another coding-agent interface and ask:

> Start today's French session. Read `AGENTS.md`, `settings.md`, `session/current.md`, and the relevant memory files first.

The tutor should adapt the session to current progress, recurring mistakes, mastery, and the curriculum. At the end, it updates `session/current.md` and only the memory files affected by the lesson.

## Repository model

- `AGENTS.md` — operating contract for coding agents
- `skill.md` — tutor behavior and session protocol
- `settings.md` — learner-adjustable defaults
- `session/current.md` — short-lived working state and next-session handoff
- `memory/` — durable learner state
- `curriculum/` — progression and TEF preparation
- `lessons/` — completed lesson records and templates
- `skills/` — specialist tutor roles
- `quizzes/`, `exercises/`, `exams/` — practice and assessment assets
- `automation/` — future prompts and scripts

## Current status

The repository contains the initial architecture and templates. Personalization begins by filling in `memory/profile.md` and running the first diagnostic session.
