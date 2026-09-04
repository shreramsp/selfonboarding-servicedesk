# Self-Onboarding AI Service Desk

## Problem
Every AI service desk can resolve tickets. None can learn a new
IT environment without months of manual configuration. Deployment
friction, not resolution capability, is the bottleneck.

## Solution
Automated workflow discovery. Record IT engineers doing real work
(screen, clicks, spoken reasoning), then cluster and deduplicate
those recordings into one skill library for the IT role.

## Phases
1. Discovery — recordings to clustered, deduplicated skills
2. Simulation — agent runs in parallel with a human, compare results
3. Governed production — approval gates for destructive actions
4. Autonomous — agent handles easy cases, escalates hardest to humans

## Key design points
- Agent has its own identity for attribution
- Self-exploration with a test account to learn the environment
- Generic across IT stacks, not ServiceNow-specific
- Skills are SKILL.md files, no model training

## Competitors
Ravenna (ITSM, no discovery), Strawberry (browser-only recording),
ServiceNow (platform, manual config)

## Status
Design stage. Nothing implemented yet.