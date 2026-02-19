---
description: Review and score a pitch deck or fundraising narrative against VC first principles
argument-hint: [path to pitch deck or description of your company]
allowed-tools: [Read, Glob, Grep, WebSearch, WebFetch, Task]
---

# Pitch Review

You are conducting a comprehensive review of a founder's pitch deck or fundraising narrative using the VC Fundraising first principles framework.

## Input

The user provided: $ARGUMENTS

## Process

### Step 1: Gather Context

If the user provided a file path, read the pitch deck or document. If they provided a description, ask clarifying questions to understand:

1. **The Company:** What do you do? Single sentence.
2. **The Problem:** What pain are you solving? For whom?
3. **The Insight:** What do you see that others don't? How did you earn this insight?
4. **Why Now:** What changed to make this possible/necessary?
5. **Traction:** Key metrics (MRR, growth rate, users, retention)
6. **Market:** Who is the customer? How big is the opportunity?
7. **Team:** Why are you the ones to build this?
8. **Stage:** What round are you raising? How much?

### Step 2: Launch Pitch Analyst

Launch the `pitch-analyst` agent with the gathered context. Ask it to evaluate across all 11 dimensions. Instruct the agent to apply its thinking toolkit where scoring reveals weaknesses: use first-principles decomposition on any dimension scoring 2 or below, red-team the overall pitch, and use inversion to identify what would guarantee a VC pass.

### Step 3: Synthesize and Present

Present the findings to the user:

1. **Overall Assessment** -- Letter grade with 2-sentence summary
2. **Scorecard** -- Table of 11 dimensions with scores and one-line feedback each
3. **The 30-Second Retell** -- How a VC champion would describe this to their partnership
4. **Top 3 Wins** -- What's compelling
5. **Top 3 Fixes** -- What must change before pitching, with specific rewrites
6. **Stage Fit** -- Is the narrative appropriate for the fundraising stage?

### Step 4: Offer Next Steps

Ask the user if they'd like to:
- Deep-dive on any specific dimension
- Get help rewriting weak sections
- Practice Q&A for their pitch
- Build a complete narrative from scratch
