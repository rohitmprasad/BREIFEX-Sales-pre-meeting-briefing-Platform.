Breifex – Slack-native AI Sales Copilot for EdTech

Breifex is a Slack-native AI personal assistant that creates **meeting-ready pre‑meeting briefs in under 10 minutes**, built entirely on a no-code automation platform.

## 1. Problem & Persona

- Persona: Priya, EdTech institutional sales rep in India (Tier‑2/3).
- Pain: ~50 minutes of prep per meeting across Salesforce, LinkedIn, Gmail, Google, and Notion.
- Need: Faster, more confident meeting prep with less context switching.

## 2. What Breifex Does

Briefex generates a single, CEO-ready brief for every meeting:
- Company intel and account context.
- Attendee mapping and LinkedIn summaries.
- Objection handling scripts.
- Conversation starters and next-step suggestions.

Core benefit: **Focus on strategic selling, not researching.**

## 3. Impact (Pilot Metrics)

- Time: 50 min → 9 min per meeting (~82% reduction).
- Rep confidence: 5/10 → 9/10.
- Deal advancement: 60% → 85% of meetings advancing.

These numbers come from early pilot usage and are central to the product narrative.

## 4. Architecture (No-code Stack)

This project was built using a no-code platform:

- Trigger: New upcoming meeting / Slack command from the rep.
- Data sources: CRM (e.g., Salesforce), LinkedIn, email, web search, internal notes (Notion).
- Orchestration: No-code workflows to fetch data, call AI models, and assemble a brief.
- Output: Slack message/doc with a structured pre‑meeting brief.

See [`docs/architecture.md`](docs/architecture.md) for a detailed flow diagram.

## 5. Workflow & Screenshots

- `images/workflow.png`: High‑level agent workflow in the no-code platform.
- `images/brief-example.png`: Sample pre‑meeting brief sent to Slack.

## 6. Market & Positioning (for PM / GTM reviewers)

- Market: Global EdTech ~\$163B (2024) growing to ~\$572B (2034).
- Focus: ~50K addressable EdTech sales reps; Year‑1 SOM 100–200 reps.
- Edge:
  - Slack-native, in‑workflow assistant.
  - EdTech‑specific playbooks and prompts.
  - India Tier‑2/3 institutional sales teams (underserved, high pain).

## 8. How to Use This Repo

This repo is intended as a **portfolio case study**:
- For PM roles: Shows my ability to define problem, design solution, and quantify impact.
- For AI / no‑code roles: Demonstrates orchestrating AI-powered workflows without writing backend code.
