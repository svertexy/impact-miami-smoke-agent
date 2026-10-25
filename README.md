# Impact Miami Smoke-Test Agent

A minimal Vercel agent smoke test for the Impact Miami hackathon. It validates the smallest useful agent loop: read a small project dataset, group by status, flag at-risk records, and cite the source record names.

- Deployed agent: `impact-miami-smoke-agent` in the Six Star Vision Vercel team.
- Sample data: [`sample-projects.json`](sample-projects.json)
- Agent contract: [`agent-instructions.md`](agent-instructions.md)

This repository contains synthetic data only. Runtime credentials belong in Vercel environment variables and are never committed.
