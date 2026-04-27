# 🤖 Enterprise AI Agent Prompt Library

A collection of production-grade, universal AI agent prompts designed for large-scale project execution. Each agent is a specialist. Agent 05 is the quality layer that rides alongside all of them.

Copy any prompt file into your AI assistant (Claude, GPT-4, Gemini, etc.) and start working immediately.

---

## 📦 Agents Included

| File | Agent | Role |
|---|---|---|
| `agent-01-analytics-martech.md` | **Agent 01** | Senior Analytics / Digital Analytics / Martech |
| `agent-02-digital-marketer.md` | **Agent 02** | Senior Digital Marketer & Growth Strategist |
| `agent-03-cobol-developer.md` | **Agent 03** | Principal COBOL / Mainframe Developer |
| `agent-05-monitor-improve.md` | **Agent 05** | Monitor, Evaluate & Improve (always paired) |

> ⚠️ **Agent 04** is reserved for future expansion (Frontend / Full-Stack Developer Agent).

---

## 🚀 How to Use

### Step 1 — Pick your agent(s)
Choose the primary agent for your task:
- Analytics, tracking, data layer, CDP, attribution → **Agent 01**
- Campaigns, SEO, email, paid media, growth → **Agent 02**
- COBOL programs, JCL, VSAM, DB2, CICS → **Agent 03**

### Step 2 — Always add Agent 05
**Agent 05 must always accompany the primary agent.** It monitors output quality and produces improvement reports.

### Step 3 — Paste both prompts into your AI assistant
Open your AI assistant and paste the contents of:
1. Your chosen primary agent prompt (e.g., `agent-01-analytics-martech.md`)
2. `agent-05-monitor-improve.md`

Both prompts can be provided as separate system messages, or concatenated into one system prompt.

### Step 4 — Start your session
Describe your project task. The primary agent executes. Agent 05 monitors.

### Step 5 — Review the end-of-session report
At the end of your session, ask Agent 05 for the evaluation report:
> *"Agent 05, please produce the end-of-session evaluation report."*

Use the report to improve your prompts and your own prompting style over time.

---

## 🔗 Agent Pairing Reference

| Task Type | Primary Agent | + Monitor |
|---|---|---|
| GA4 audit, tagging spec, data layer design | Agent 01 | Agent 05 |
| Martech architecture, CDP setup, attribution | Agent 01 | Agent 05 |
| Paid media campaigns, ad copy, GTM strategy | Agent 02 | Agent 05 |
| SEO content briefs, email flows, CRO | Agent 02 | Agent 05 |
| COBOL batch programs, JCL, DB2 SQL | Agent 03 | Agent 05 |
| CICS programs, VSAM, mainframe modernization | Agent 03 | Agent 05 |
| Multi-domain project (e.g., analytics + marketing) | Agent 01 + Agent 02 | Agent 05 |

---

## ✨ Design Principles

These prompts are built on four principles:

1. **Universal** — No hardcoded company names, tools, or URLs. Every prompt works for any project by any user.

2. **Self-documenting** — Each agent produces structured deliverables with consistent templates. The output is always professional and organized.

3. **Standards-enforcing** — Each agent has explicit behavioral rules (e.g., COBOL file status is always handled, marketing copy always has 3 variants, analytics plans always include a QA checklist).

4. **Continuously improving** — Agent 05 creates a feedback loop. Each session produces a report that makes the next session better.

---

## 🛠️ Customization Guide

These prompts are designed to be adapted. Here's where to make changes:

### Adding your company context
In any agent prompt, after the `## Identity & Role` section, add:

```markdown
## Project Context
- Company: [Your Company]
- Industry: [Your Industry]
- Tech Stack: [Relevant tools already in use]
- Constraints: [Budget, compliance requirements, team size]
```

### Restricting to specific tools
If you only use certain platforms (e.g., only Adobe Analytics, not GA4), edit the `## Core Competencies` section to remove tools you don't use. This prevents the agent from recommending irrelevant tools.

### Adjusting output verbosity
Each agent has an `## Interaction Style` section. Add a line like:
- `"Keep responses concise — maximum 300 words per section."` for quick answers
- `"Always produce full, production-ready deliverables."` for complete output

---

## 📋 Contributing

To add a new agent:
1. Follow the naming convention: `agent-[NUMBER]-[role].md`
2. Include all required sections: Identity & Role, Core Competencies, Behavioral Rules, Deliverable Templates, Interaction Style, Session Handoff block
3. Make sure the Session Handoff block outputs a summary compatible with Agent 05
4. Update this README's agent table

---

## 📄 License

MIT — free to use, adapt, and distribute. Attribution appreciated but not required.
