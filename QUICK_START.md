# Quick Start: Essential Trinity in 5 Minutes ⚡

Get the essential MCP servers running in your environment in just 5 minutes.

## Prerequisites

- Node.js 18+ installed
- One of: Claude Desktop, Cursor, or other MCP-compatible IDE
- Your project path ready

---

## Step 1: Locate Config File

### Claude Desktop (macOS)
```bash
~/Library/Application Support/Claude/claude_desktop_config.json
```

### Claude Desktop (Windows)
```bash
%APPDATA%\Claude\claude_desktop_config.json
```

### Cursor
```bash
cursor mcp add
# Or manually edit similar path
```

---

## Step 2: Copy This Config

**Replace `/Users/yourname/projects` with your actual project path**

```json
{
  "mcpServers": {
    "context7": {
      "command": "npx",
      "args": ["-y", "@upstash/context7-mcp"]
    },
    "sequential-thinking": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]
    },
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/Users/yourname/projects"]
    }
  }
}
```

### For GitHub Integration (Optional)

Add this to `mcpServers` after generating a personal access token:

```json
"github": {
  "command": "npx",
  "args": ["-y", "@github/github-mcp-server"],
  "env": {
    "GITHUB_PERSONAL_ACCESS_TOKEN": "ghp_your_token_here"
  }
}
```

**Get GitHub token:** https://github.com/settings/tokens (select `repo` scope)

---

## Step 3: Restart IDE

⚠️ **CRITICAL: Full restart required**

- Close your IDE completely
- Reopen it
- MCPs will download automatically on first run (~30 seconds)

---

## Step 4: Test It Works

Open a chat and send:

```
Use context7 to look up the latest React documentation, 
then use sequential thinking to break down a component architecture plan,
finally use filesystem to list my project structure.
```

✅ If you see tool calls in the response, it's working!

---

## Troubleshooting

### "MCP server not found"
**Solution:** Did you restart the IDE? Restart it again.

### "filesystem: Path not found"
**Solution:** Use absolute path, not relative.
- ❌ Wrong: `"./projects"`
- ✅ Right: `"/Users/you/projects"` (Mac) or `"C:/Users/You/projects"` (Windows)

### "Too many tokens"
**Solution:** You probably installed too many MCPs. Start with just these 3.

### "Permission denied"
**Solution:** When prompted "Allow access?", click "Allow for this chat" or "Always allow".

---

## Next Steps

Once working, consider adding:

### For GitHub work:
```json
"github": {
  "command": "npx",
  "args": ["-y", "@github/github-mcp-server"],
  "env": {"GITHUB_PERSONAL_ACCESS_TOKEN": "your_token"}
}
```

### For web testing:
```json
"playwright": {
  "command": "npx",
  "args": ["-y", "@playwright/test"]
}
```

### For database work:
```json
"supabase": {
  "command": "npx",
  "args": ["-y", "@supabase/mcp-server"]
}
```

**Pro tip:** Add one MCP per week, not all at once. This lets you understand what each one does and manage token costs.

---

## Real Example: Full Config

```json
{
  "mcpServers": {
    "context7": {
      "command": "npx",
      "args": ["-y", "@upstash/context7-mcp"]
    },
    "sequential-thinking": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]
    },
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/Users/yourname/projects"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@github/github-mcp-server"],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "ghp_xxxxxxxxxxxx"
      }
    }
  }
}
```

---

## Questions?

Check the main [README.md](README.md) for detailed explanations, or open an issue with your specific setup.

**Estimated time remaining:** 2-3 minutes to restart and verify. You're almost done!
