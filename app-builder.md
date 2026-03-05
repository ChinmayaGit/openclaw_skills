# app-builder Skill Package

Contains full skill folder for **neo-app-mode** so others can use it directly.

## How to Use

### Option 1: Manual install (recommended for sharing zip)
1. Download and extract the zip file.
2. Copy the folder `neo-app-mode` into your OpenClaw skills directory:
   - Usually: `~/.openclaw/workspace/skills/`
3. Confirm `SKILL.md` exists at:
   - `~/.openclaw/workspace/skills/neo-app-mode/SKILL.md`
4. Restart/reload your OpenClaw session if needed.

### Option 2: Keep in project repo
1. Place the skill folder in your repo under `skills/`.
2. Commit and share the repo.
3. Team members pull the repo and use the skill normally.

### (Optional) Publish to ClawHub
```bash
clawhub publish ./neo-app-mode --slug app-builder --name "app-builder" --version 1.0.0 --changelog "Initial publish"
```

## Package Contents

- `neo-app-mode/SKILL.md`
- `neo-app-mode/references/default-requirements.md`
- `neo-app-mode/scripts/scaffold_neo_app.sh`

Total files: **3**
Generated: 2026-03-06T00:09:58
