# Tap-in-version-1

**Tap In** — an AI-driven and agentic people analytics and workflow amplifier, built for HR Business Partners, the managers they support, and central People teams.

🔗 **Live demo:** https://yomiogbalaja.github.io/Tap-in-version-1/

## What's in this prototype

- Three role-based dashboards: Manager/Partner, HR Business Partner, and People Team
- Performance benchmarking, 9-box grid, stack ranking, and manager/team scorecards
- Talent planning, succession planning, and a workforce planner (competency + bench strength)
- Automated exit-interview tracking and trends
- An Employee Relations tracker (SLA compliance, SOP milestones, recurring themes)
- Org diagnostics with a bottleneck-diagnostic agent (spans of control, management density, workload pressure, decision latency)
- An HRBP automation agent that drafts a weekly action plan
- A data architecture view (HRIS/ADP/Greenhouse/Slack sources in, write-backs out)

All data is simulated — this is a demo workspace, not connected to a real HRIS.

**Note on this static deployment:** the AI-powered features (the "Ask Tap In" assistant, the HRBP Automation Agent, the Org Diagnostics bottleneck agent, and the CSV/PDF download buttons) call a Claude-runtime capability that's only available when this app is opened as a Claude Artifact. On this plain GitHub Pages hosting, every dashboard, chart, and data view works fully — those specific AI-agent and export buttons will show a graceful "not available" message instead of running.
