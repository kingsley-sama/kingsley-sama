# Hi, I'm Kingsley Okpo 👋

**Software engineer · AI engineer · AI code evaluator**
I build production systems with AI coding agents, and I evaluate whether those agents think like strong engineers.

📍 Lagos, Nigeria (remote, UTC+1) · ✉️ [kngsley2018@gmail.com](mailto:kngsley2018@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/kingsley-okpo/) · 🌐 [kingsleyokpo.tech](https://kingsleyokpo.tech)

---

### What I do

- **Build with coding agents.** Claude Code is my daily pair. I've shipped production TypeScript/Next.js apps with it, and every repo below carries a `CLAUDE.md` or `AGENTS.md` that tells agents how the codebase really works.
- **Evaluate AI-generated code.** As an AI trainer at Mindrift and micro1, I scored coding-agent responses on plan, reasoning, code and explanation. I wrote down why a response is a 2 and not a 4, and flagged answers that are technically correct but unhelpful.
- **Ship AI into real workflows.** I build LLM pipelines (OpenAI and Claude) and n8n automations with dry-run modes, idempotent processing and honest failure handling.

### How I judge an agent's work

> Does the plan make sense? Does the explanation help, or just repeat the code?
> Does it raise the risks a strong engineer would raise? Would I trust it in my own codebase?

---

### Featured work

| Project | What it is | Stack |
|---|---|---|
| [**approval**](https://github.com/kingsley-sama/approval) | Client revision and annotation platform. Clients pin comments and draw on images through permission-scoped share links. Includes a versioned REST API for automation and a Playwright E2E suite. Built end to end with Claude Code. | Next.js · TypeScript · Supabase · Playwright |
| [**proposal-generator**](https://github.com/kingsley-sama/proposal-generator) | Generates branded proposals as Word documents, covering 21 service types with tiered pricing. Cut preparation time by 85%. The `CLAUDE.md` steers agents to the 200-line template generator and away from the 1,730-line legacy one. | Next.js · TypeScript · docxtemplater |
| [**delphi**](https://github.com/kingsley-sama/delphi) | An education platform with registration and a readiness test. Its `AGENTS.md` makes agents read the version-specific Next.js 16 docs before writing code, so they don't fall back on outdated training-data patterns. | Next.js 16 · React 19 · Supabase |
| [**markupio-clickup automation**](https://github.com/kingsley-sama/n8n-automation-markupio-clickup) | Headless-browser service that extracts client feedback threads and screenshots from Markup.io. It deduplicates by URL, replaces images instead of duplicating them, logs errors to the database, and exposes a REST API that n8n uses to feed ClickUp. | Node.js · Playwright · Supabase · n8n |

---

### Toolbox

- **Languages:** Python · TypeScript · JavaScript · Go · SQL
- **AI:** Claude Code · Claude API · OpenAI API · prompt design and evaluation · MCP
- **Backend and data:** Next.js · Node.js · PostgreSQL · Supabase · Drizzle · REST APIs
- **Automation and infrastructure:** n8n (self-hosted) · Docker · Linux · Playwright · Git

---

<sub>Currently: AI Engineer at Shae AI · Co-founder at Delphi Education Hub</sub>
