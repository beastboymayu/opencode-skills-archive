# OpenCode Skills Archive

A comprehensive collection of 591 skills and utilities for OpenCode AI assistant.

## Contents

### 1. Skills (591 skills)
- **File:** `skills_archive.tar.gz` (92MB)
- Extract: `tar -xzvf skills_archive.tar.gz`
- Location: Copy to `~/.agents/skills/`

### 2. Scripts
- **File:** `scripts_only.tar.gz` (9KB)
- Extract: `tar -xzvf scripts_only.tar.gz`
- Location: Copy to `~/.config/opencode/scripts/`

### 3. Full Package (scripts + tools + configs)
- **File:** `scripts_tools.tar.gz` (13KB)
- Extract: `tar -xzvf scripts_tools.tar.gz`
- Location: Copy to `~/.config/opencode/`


## Individual Files

| File | Description |
|------|-------------|
| `AGENTS.md` | Agent configuration |
| `opencode.json` | OpenCode config (secrets redacted) |
| `WORKFLOWS.md` | Predefined workflows |
| `package.json` | Dependencies |
| `.gitignore` | Git ignore rules |
| `tools/grep.py` | Grep utility |
| `tools/list-tools.sh` | List tools script |

## Scripts Included

| Script | Purpose |
|--------|---------|
| `install-skill.sh` | Install skills from GitHub |
| `auto-install-skill.sh` | Auto-install workflow |
| `lookup-skill.sh` | Search and discover skills |
| `skill-installer-agent.sh` | Agent-based installation |
| `analyze-project.sh` | Project analysis |
| `health-check.sh` | Health check |
| `dep-audit.sh` | Dependency audit |
| `quality-check.sh` | Quality check |
| `run-tests.sh` | Run tests |

## Installation

```bash
# Extract skills
tar -xzvf skills_archive.tar.gz
cp -r skills/* ~/.agents/skills/

# Extract scripts
tar -xzvf scripts_only.tar.gz
cp -r scripts/* ~/.config/opencode/scripts/
```

## Configuration

Edit `opencode.json` and replace placeholder API keys:
- `YOUR_API_KEY_HERE` - LLM provider API key
- `YOUR_NVIDIA_API_KEY_HERE` - NVIDIA NIM API key
- `YOUR_GITHUB_TOKEN_HERE` - GitHub personal access token

## Repository

- **GitHub:** https://github.com/beastboymayu/opencode-skills-archive
- **Skills:** 591 skills in `/.agents/skills/`

---

*Generated for OpenCode AI assistant configuration backup*