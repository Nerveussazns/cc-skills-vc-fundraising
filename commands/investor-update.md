---
description: Draft a monthly investor update email from your metrics and company context
argument-hint: [key metrics and highlights for the month]
allowed-tools: [Read, Glob, Grep, Task]
---

# Investor Update

You are helping a founder write a monthly investor update that builds trust, projects momentum, and drives specific asks.

## Input

The user provided: $ARGUMENTS

## Process

### Step 1: Gather Monthly Data

If the user hasn't provided complete information, ask for:

**Metrics:**
- MRR/ARR and month-over-month change
- Key growth metric (users, customers, engagement) and MoM change
- Burn rate and remaining runway
- One key ratio (LTV/CAC, retention, NPS, churn)

**Qualitative:**
- 2-3 biggest wins this month (be specific: customer names, deal sizes, feature launches)
- 1-2 biggest challenges or misses (be honest)
- Any team changes (hires, departures, open roles)
- What's planned for next month

**Asks:**
- What specific help do you need from investors?
- Any customer intros you're seeking? (name specific companies/people)
- Any hiring needs? (specific roles and requirements)
- Any strategic decisions you want input on?

### Step 2: Draft the Update

Launch the `investor-update-writer` agent with all gathered context. Instruct it to apply its thinking toolkit: frame metrics as an interconnected system, narrate reinforcing loops in the growth story, show second-order implications of key metric changes, and use inversion to frame any challenges. Request a complete update in the 5-15 format.

### Step 3: Present and Refine

Present the draft update with:
- Subject line
- Full email body
- Notes on tone and any adjustments recommended

Ask the user:
- Is the tone right? (Some founders prefer more casual, some more formal)
- Should we add or remove any metrics?
- Are the "Where I Need Help" asks specific enough?
- Any sensitive information that should be excluded?

### Step 4: Final Touches

- Adjust based on feedback
- Remind user to send to both existing investors AND warm prospective investors
- Suggest adding to a consistent monthly cadence (same day each month)
