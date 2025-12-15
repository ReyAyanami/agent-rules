# Agent Rules

Personal guidelines for LLM agents working on my projects.

## Usage in Projects

### Option 1: Git Submodule (Recommended)

```bash
# In your project root
git submodule add git@github.com:ReyAyanami/agent-rules.git .agent-rules

# Clone project with submodules
git clone --recurse-submodules <your-repo>

# Or update existing clone
git submodule update --init
```

Reference in conversations: "See `.agent-rules/AGENT_GUIDELINES.md`"

### Option 2: Direct URL Reference

Simply reference the live document:
```
https://github.com/ReyAyanami/agent-rules/blob/main/AGENT_GUIDELINES.md
```

Paste URL at start of agent conversations.

### Option 3: Copy File

For projects that need to be self-contained:
```bash
curl -o .agent-guidelines.md https://raw.githubusercontent.com/ReyAyanami/agent-rules/main/AGENT_GUIDELINES.md
```

Add to `.gitignore` if you want to keep it external.

## Files

- **AGENT_GUIDELINES.md** - Core philosophy and working style for AI assistants