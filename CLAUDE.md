# Claude Code Context: Impact Miami Smoke-Test Agent

Repository: https://github.com/svertexy/impact-miami-smoke-agent

This is a minimal synthetic-data smoke test for the Impact Miami hackathon. The deployed Vercel agent is named `impact-miami-smoke-agent` and summarizes project records, groups by status, flags at-risk or overdue records, and cites source record names.

Read `agent-instructions.md`, `sample-projects.json`, and `README.md` before changing anything. Preserve the boundary that the sample data is synthetic and that credentials must remain in environment variables. Never request, print, commit, or paste API keys into repository files or documentation.

Acceptance test: summarize the three sample projects and flag any at risk. Expected at-risk record: Biscayne Transit Alerts (sample-record-2).
