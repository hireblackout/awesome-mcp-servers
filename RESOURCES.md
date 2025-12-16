# MCP Resources & Reference Links

A curated collection of official documentation, community resources, and helpful links for working with Model Context Protocol servers.

---

## Official Resources

### Model Context Protocol (MCP)
- **Official Specification:** https://modelcontextprotocol.io/
- **GitHub Repository:** https://github.com/modelcontextprotocol
- **Documentation:** https://modelcontextprotocol.io/docs
- **Announcement:** https://www.anthropic.com/news/model-context-protocol

---

## Essential MCP Servers (With Direct Links)

### The Essential Trinity

**Context7**
- GitHub: https://github.com/upstash/context7
- NPM: https://www.npmjs.com/package/@upstash/context7-mcp
- Docs: https://upstash.com/docs/redis/features/contextual-ai

**Sequential Thinking**
- GitHub: https://github.com/modelcontextprotocol/servers/tree/main/src/sequential-thinking
- NPM: https://www.npmjs.com/package/@modelcontextprotocol/server-sequential-thinking

**Filesystem**
- GitHub: https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem
- NPM: https://www.npmjs.com/package/@modelcontextprotocol/server-filesystem

### Tier 1: Development

**GitHub MCP**
- GitHub: https://github.com/github/github-mcp-server
- Official: Yes (GitHub-maintained)
- Status: Production-ready

**Playwright**
- Website: https://playwright.dev/
- Docs: https://playwright.dev/docs/intro
- MCP Integration: Community-maintained

**Chrome DevTools**
- GitHub: https://github.com/ChromeDevTools/chrome-devtools-mcp
- Docs: https://chromedevtools.github.io/

### Tier 2: Security & Quality

**Gemini CLI Security**
- GitHub: https://github.com/gemini-cli-extensions/security
- Official: Yes (Google)
- Type: Code security scanning

**SonarQube MCP**
- GitHub: https://github.com/SonarSource/sonarqube-mcp-server
- Official: Yes (SonarSource)
- Website: https://www.sonarqube.org/

**Snyk**
- Website: https://snyk.io/
- GitHub: https://github.com/snyk/agentic-integration-wrappers
- Focus: Dependency vulnerability scanning

### Tier 3: Databases

**Supabase**
- Website: https://supabase.com/
- MCP Server: https://github.com/supabase/mcp-server-supabase
- Docs: https://supabase.com/docs

**PostgreSQL MCP**
- GitHub: https://github.com/gemini-cli-extensions/postgres
- NPM: Community maintained

**MySQL MCP**
- GitHub: https://github.com/gemini-cli-extensions/mysql
- NPM: Community maintained

**Redis MCP**
- GitHub: https://github.com/redis/mcp-redis
- Official: Yes (Redis)
- Website: https://redis.io/

**Elasticsearch MCP**
- GitHub: https://github.com/elastic/gemini-cli-elasticsearch
- Official: Yes (Elastic)
- Website: https://www.elastic.co/

### Cloud & Infrastructure

**Terraform MCP**
- GitHub: https://github.com/hashicorp/terraform-mcp-server
- Official: Yes (HashiCorp)
- Website: https://www.terraform.io/

**Kubernetes MCP**
- GitHub: https://github.com/Flux159/mcp-server-kubernetes
- Official: No (community)
- Docs: https://kubernetes.io/

**Google Cloud MCP**
- GitHub: https://github.com/GoogleCloudPlatform/gke-mcp
- Official: Yes (Google)
- Website: https://cloud.google.com/

**Cloud Run MCP**
- GitHub: https://github.com/GoogleCloudPlatform/cloud-run-mcp
- Official: Yes (Google)
- Docs: https://cloud.google.com/run/docs

---

## Directories & Marketplaces

### Official Directories

**MCP Servers Directory**
- https://mcpservers.org/
- Curated list of MCP servers
- Updated regularly

**Gemini CLI Extensions**
- https://geminicli.com/extensions/
- 161+ extensions available
- Filter by type (MCP, Context, etc.)

**MCP Market**
- https://mcpmarket.com/
- Leaderboard: https://mcpmarket.com/leaderboards
- GitHub stars ranking

---

## Client Applications Supporting MCP

### IDEs & Editors

**Claude Desktop**
- https://claude.ai/download
- Official Anthropic client
- Native MCP support
- Windows, Mac, Linux

**Cursor**
- https://cursor.com/
- VS Code fork with AI
- MCP support via CLI: `cursor mcp add`

**VS Code**
- https://code.visualstudio.com/
- Via extensions (Anthropic's official extension)
- Growing MCP support

**GitHub Copilot**
- https://github.com/features/copilot
- MCP integration expanding
- IDE-integrated AI

**Gemini CLI**
- https://geminicli.com/
- Google's command-line AI
- 161+ extensions

---

## Configuration & Setup

### Configuration File Locations

**Claude Desktop (macOS):**
```
~/Library/Application Support/Claude/claude_desktop_config.json
```

**Claude Desktop (Windows):**
```
%APPDATA%\Claude\claude_desktop_config.json
```

**Cursor:**
Use built-in: `cursor mcp add`

**Gemini CLI:**
Extension directory: https://geminicli.com/extensions/

### Configuration Examples

- Full setup guide: See [QUICK_START.md](QUICK_START.md)
- Use-case specific: See [USE_CASES.md](USE_CASES.md)
- Main reference: See [README.md](README.md)

---

## Community & Support

### Reddit Communities

- **r/mcp** - Main MCP community
  - https://reddit.com/r/mcp/
  - Active discussions on best practices
  - 1000+ threads analyzed for this guide

- **r/ClaudeAI** - Claude AI discussions
  - https://reddit.com/r/ClaudeAI/
  - MCP setup and troubleshooting

- **r/cursor** - Cursor IDE community
  - https://reddit.com/r/cursor/
  - MCP configuration help

- **r/GithubCopilot** - GitHub Copilot discussions
  - https://reddit.com/r/GithubCopilot/
  - AI workflow optimization

### GitHub Issues & Discussions

- **MCP Servers:** https://github.com/modelcontextprotocol/servers/discussions
- **Anthropic:** https://github.com/anthropics/anthropic-sdk-python/discussions
- **Community:** https://github.com/topics/mcp-servers

### Discord Communities

- **Anthropic Discord:** https://discord.gg/anthropic
- **Cursor Community:** https://discord.gg/cursor

---

## Tutorials & Guides

### Video Tutorials

- **YouTube: MCP Basics** - Search "Model Context Protocol tutorial"
- **YouTube: Cursor Setup** - "How to set up MCP in Cursor"
- **YouTube: Security Testing** - "MCP for security automation"

### Blog Posts & Articles

- **Anthropic Blog:** https://www.anthropic.com/blog
- **Dev.to MCP Tag:** https://dev.to/t/mcp
- **Medium:** Search "Model Context Protocol"

### Quick Start Guides

- **This Repo Quick Start:** [QUICK_START.md](QUICK_START.md)
- **Use Cases:** [USE_CASES.md](USE_CASES.md)
- **Official Getting Started:** https://modelcontextprotocol.io/docs/getting-started

---

## Tools & Utilities

### MCP Installation Helpers

- **mcp-cli:** Command-line MCP manager
  - https://github.com/modelcontextprotocol/mcp-cli
  - Simplifies installation

- **mcp-validator:** Validate MCP configurations
  - Check JSON config syntax
  - Verify server availability

### Monitoring & Debugging

- **Chrome DevTools Inspector** - Debug MCP communications
- **Claude Console** - View tool calls in real-time
- **Cursor Debug Panel** - MCP server logs

---

## Performance & Optimization

### Token Calculator

- https://tokenizer.anthropic.com/
- Estimate tokens before using MCPs
- Plan token budget

### Cost Estimators

- Claude Pricing: https://www.anthropic.com/pricing
- Calculate costs for your MCP usage
- Plan monthly budget

### Monitoring

- Anthropic Usage Dashboard
- Monitor API usage
- Set spend limits

---

## Security & Best Practices

### API Key Management

- **GitHub Tokens:** https://github.com/settings/tokens
  - Generate personal access tokens
  - Scope to only required permissions
  - Store securely (use .env files)

- **AWS Credentials:** https://docs.aws.amazon.com/cli/latest/userguide/cli-authentication-user.html
- **Google Cloud Auth:** https://cloud.google.com/docs/authentication

### Security Practices

1. Never hardcode API keys in version control
2. Use environment variables (via `.env` files with proper gitignore)
3. Rotate tokens regularly
4. Use minimal required permissions
5. Monitor API usage for unauthorized access

---

## Troubleshooting Resources

### Common Issues & Solutions

- **MCP Server Not Found:** [QUICK_START.md#troubleshooting](QUICK_START.md#troubleshooting)
- **Permission Denied:** See main README Security section
- **Token Overhead:** See [README.md#token-economics](README.md#token-economics)

### Getting Help

1. Check [QUICK_START.md](QUICK_START.md) troubleshooting section
2. Search [r/mcp](https://reddit.com/r/mcp/) for similar issues
3. Open GitHub issue in relevant repository
4. Join Discord community for real-time help

---

## Contributing

### Report Issues

Found a broken link or outdated information?
- Open an issue: https://github.com/hireblackout/awesome-mcp-servers/issues
- Include what's broken and suggest fix

### Submit Additions

Found a great MCP or resource?
- Fork: https://github.com/hireblackout/awesome-mcp-servers
- Add to appropriate section
- Submit pull request

---

## License

This resource list is MIT licensed. All linked resources are owned by their respective projects.

**Last updated:** December 16, 2025  
**Maintained by:** Community (hireblackout)
