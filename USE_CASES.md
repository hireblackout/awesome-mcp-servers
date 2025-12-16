# MCP Server Recommendations by Use Case

Find the perfect MCP setup for your specific workflow.

---

## 🔒 Cybersecurity & Penetration Testing

### Essential Trinity
- Context7
- Sequential Thinking
- Filesystem

### Recommended Stack

1. **Context7** - Keep security documentation current (OWASP, CVE databases, tool docs)
2. **Sequential Thinking** - Break down vulnerabilities: attack surface → exploitation → mitigation
3. **Filesystem** - Explore target codebases, security research projects
4. **GitHub** - Manage exploit repos, research collaboration
5. **SonarQube** - Identify code vulnerabilities with AI analysis
6. **Gemini CLI Security** - Catch security issues in code changes
7. **Chrome DevTools** - Test XSS, CSRF, CSP violations in web apps
8. **Snyk** - Audit dependency vulnerabilities

### Configuration

```json
{
  "mcpServers": {
    "context7": {"command": "npx", "args": ["-y", "@upstash/context7-mcp"]},
    "sequential-thinking": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]},
    "filesystem": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/security/projects"]},
    "github": {
      "command": "npx",
      "args": ["-y", "@github/github-mcp-server"],
      "env": {"GITHUB_PERSONAL_ACCESS_TOKEN": "your_token"}
    }
  }
}
```

### Example Workflow

```
1. Use Context7 to look up latest OWASP Top 10
2. Use Sequential Thinking to identify vulnerability chain
3. Use Filesystem to examine target code
4. Use GitHub to document findings
5. Use Chrome DevTools to manually test findings
```

---

## 🏃 Competitive Programming

### Essential Trinity
- Context7
- Sequential Thinking  
- Filesystem

### Recommended Stack

1. **Context7** - Algorithm documentation, problem patterns
2. **Sequential Thinking** - Break down complex problems step-by-step
3. **Filesystem** - Multi-file solution management
4. **GitHub** - Version control, contest submissions
5. **Memory Bank** - Remember previously solved similar problems

### Configuration

```json
{
  "mcpServers": {
    "context7": {"command": "npx", "args": ["-y", "@upstash/context7-mcp"]},
    "sequential-thinking": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]},
    "filesystem": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/competitive/solutions"]},
    "github": {
      "command": "npx",
      "args": ["-y", "@github/github-mcp-server"],
      "env": {"GITHUB_PERSONAL_ACCESS_TOKEN": "your_token"}
    }
  }
}
```

### Example Workflow

```
Problem: Graph traversal with dynamic constraints

1. Context7: Look up DFS/BFS/Dijkstra patterns
2. Sequential Thinking: 
   - Understand input format
   - Identify constraint type
   - Choose algorithm
   - Plan implementation
3. Filesystem: Write solution across multiple files
4. Test locally before submission
5. GitHub: Push solution with explanation
```

---

## 🚀 Full-Stack Web Development

### Essential Trinity
- Context7
- Sequential Thinking
- Filesystem

### Recommended Stack

1. **Context7** - Latest framework docs (React, Next.js, Vue)
2. **Sequential Thinking** - Architecture planning
3. **Filesystem** - Multi-file component development
4. **GitHub** - PR management, collaboration
5. **Playwright** - E2E testing, self-testing code
6. **Supabase** - Database schema exploration & queries
7. **Chrome DevTools** - Debugging, performance analysis
8. **Firebase** - Backend services integration

### Configuration

```json
{
  "mcpServers": {
    "context7": {"command": "npx", "args": ["-y", "@upstash/context7-mcp"]},
    "sequential-thinking": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]},
    "filesystem": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/web/project"]},
    "github": {
      "command": "npx",
      "args": ["-y", "@github/github-mcp-server"],
      "env": {"GITHUB_PERSONAL_ACCESS_TOKEN": "your_token"}
    },
    "supabase": {
      "command": "npx",
      "args": ["-y", "@supabase/mcp-server"]
    }
  }
}
```

### Example Workflow

```
Feature: User profile with dynamic data

1. Context7: Fetch Next.js App Router best practices
2. Sequential Thinking: Plan component hierarchy
3. Filesystem: Scaffold folder structure
4. Supabase: Design & query schema
5. Code components
6. Playwright: Auto-test components
7. GitHub: Create PR with tests
```

---

## 🎯 Hackathon Projects

### Essential Trinity
- Context7
- Sequential Thinking
- Filesystem

### Recommended Stack

1. **Context7** - Quick documentation lookups
2. **Sequential Thinking** - Feature prioritization
3. **Filesystem** - Rapid prototyping
4. **GitHub** - Team collaboration, branching
5. **Cloud Run** - Instant deployment
6. **Terraform** - Infrastructure setup
7. **Postman** - API testing
8. **Firebase** - Backend without server setup

### Configuration

```json
{
  "mcpServers": {
    "context7": {"command": "npx", "args": ["-y", "@upstash/context7-mcp"]},
    "sequential-thinking": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]},
    "filesystem": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/hackathon"]},
    "github": {
      "command": "npx",
      "args": ["-y", "@github/github-mcp-server"],
      "env": {"GITHUB_PERSONAL_ACCESS_TOKEN": "your_token"}
    }
  }
}
```

### 36-Hour Timeline

**Hours 0-6:** Planning
- Sequential Thinking: Break down project into MVP + nice-to-have
- GitHub: Create project board
- Context7: Gather library docs

**Hours 6-24:** Development
- Filesystem: Scaffold & code
- Context7: Real-time documentation
- GitHub: Frequent commits

**Hours 24-30:** Testing & Polish
- Playwright: Add tests
- Chrome DevTools: UI polish

**Hours 30-36:** Deployment & Demo
- Cloud Run: Deploy
- GitHub: Final push

---

## 🔧 IoT & Embedded Systems

### Essential Trinity
- Context7
- Sequential Thinking
- Filesystem

### Recommended Stack

1. **Context7** - Arduino/ESP32 documentation, protocol references
2. **Sequential Thinking** - Debugging hardware issues systematically
3. **Filesystem** - Sketch management across multiple files
4. **GitHub** - Version control for hardware projects
5. **Chrome DevTools** - Test web interfaces on embedded devices
6. **Redis** - Real-time sensor data caching
7. **MQTT/IoT protocols docs** (via Context7)

### Configuration

```json
{
  "mcpServers": {
    "context7": {"command": "npx", "args": ["-y", "@upstash/context7-mcp"]},
    "sequential-thinking": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]},
    "filesystem": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/arduino/sketches"]},
    "github": {
      "command": "npx",
      "args": ["-y", "@github/github-mcp-server"],
      "env": {"GITHUB_PERSONAL_ACCESS_TOKEN": "your_token"}
    }
  }
}
```

### Example Workflow

```
Project: Temperature sensor with cloud logging

1. Context7: Look up ESP32 WiFi APIs and MQTT
2. Sequential Thinking: 
   - Read sensor correctly
   - Connect to WiFi
   - Send to cloud
   - Handle disconnections
3. Filesystem: Organize sketch in multiple .ino files
4. Code & test locally
5. GitHub: Push firmware
6. Monitor with Chrome DevTools web dashboard
```

---

## 📊 Data Analysis & Research

### Essential Trinity
- Context7
- Sequential Thinking
- Filesystem

### Recommended Stack

1. **Context7** - Data science library documentation
2. **Sequential Thinking** - Research methodology planning
3. **Filesystem** - Notebook and script organization
4. **BigQuery** - Large-scale data analysis
5. **Elasticsearch** - Search across datasets
6. **Grafana** - Visualization dashboards

### Configuration

```json
{
  "mcpServers": {
    "context7": {"command": "npx", "args": ["-y", "@upstash/context7-mcp"]},
    "sequential-thinking": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-sequential-thinking"]},
    "filesystem": {"command": "npx", "args": ["-y", "@modelcontextprotocol/server-filesystem", "/path/to/research"]},
    "bigquery": {
      "command": "npx",
      "args": ["-y", "@googleapis/genai-toolbox"]
    }
  }
}
```

---

## 💬 Selecting Your Stack

### Decision Matrix

| Need | MCPs |
|------|------|
| Documentation lookups | Context7 |
| Complex reasoning | Sequential Thinking |
| Multi-file projects | Filesystem |
| Team collaboration | GitHub |
| Browser testing | Playwright, Chrome DevTools |
| Database work | Supabase, PostgreSQL, BigQuery |
| Deployment | Cloud Run, Terraform |
| Security analysis | SonarQube, Snyk, Gemini CLI Security |
| Monitoring | Grafana, Dynatrace |
| Real-time data | Redis, Elasticsearch |

### Implementation Strategy

1. **Start:** Essential Trinity (Context7, Sequential Thinking, Filesystem)
2. **Week 1:** Add GitHub
3. **Week 2:** Add domain-specific (Playwright for web, Supabase for databases, etc.)
4. **Week 3+:** Add specialized tools as needed
5. **Monitor:** Track token usage and remove unused MCPs

---

## ⚡ Pro Tips by Use Case

### For Security Researchers
- Keep Context7 updated with latest CVE databases
- Use Sequential Thinking before every security audit
- Git-store your reconnaissance findings

### For Competitive Programmers
- Create personal MCP for problem patterns
- Use Memory Bank to avoid rewriting similar solutions
- Sequential Thinking: Always break problem into I/O → Algorithm → Output

### For Web Developers
- Context7: Follow whatever framework is trending
- Playwright: Test EVERY component before commit
- Chrome DevTools: Profile performance during development

### For Hackathon Teams
- Use GitHub's team features for coordination
- Deploy early (Day 1), polish late (Day 2-3)
- Test with actual users (not just MCPs)

### For Hardware/IoT
- Context7: Star the official Arduino & ESP32 docs
- Keep Sequential Thinking for "device won't connect" moments
- GitHub: Tag firmware versions for reproducibility

---

## Questions?

Don't see your use case? Open an issue or submit a pull request!
