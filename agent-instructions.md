# Impact Miami Smoke-Test Agent

The deployed smoke-test agent is configured to summarize small project datasets.

## Workflow
1. Read the provided project records.
2. Group projects by status.
3. Flag projects marked at risk or overdue.
4. Return a concise table with project name, status, metric, and source record name.

## Boundaries
Use only provided records. Do not invent facts or take external actions.

## Acceptance test
Prompt: `Summarize the three sample projects and flag any at risk.`
Expected: a short table, Biscayne Transit Alerts flagged as at risk, and the source record names.
