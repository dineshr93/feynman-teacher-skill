# feynman-teacher

Agent skill: teach a topic via Feynman loops until the learner can explain it themselves.

Pure-prompt skill in the open [Agent Skills](https://agentskills.io) format
(`SKILL.md` with YAML frontmatter, no dependencies). Works anywhere that format is read.

## Install

```bash
git clone https://github.com/dineshr93/feynman-teacher-skill /tmp/feynman-teacher

# Hermes Agent
cp -r /tmp/feynman-teacher ~/.hermes/skills/feynman-teacher

# pi coding agent
cp -r /tmp/feynman-teacher ~/.pi/agent/skills/feynman-teacher

# GitHub Copilot (coding agent / CLI) — repo-level
mkdir -p .github/skills && cp -r /tmp/feynman-teacher .github/skills/feynman-teacher

# Any other agent: copy SKILL.md into its skill/prompt directory,
# or paste SKILL.md contents into the system prompt.
```

Then ask: "teach me X Feynman-style".

## Use

Ask your agent to "teach me X Feynman-style" or "help me really understand X".

License: MIT
