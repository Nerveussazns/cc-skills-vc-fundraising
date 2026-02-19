---
description: Prepare for tough VC Q&A by simulating investor questions and coaching responses
argument-hint: [description of your company and what round you're raising]
allowed-tools: [Read, Glob, Grep, WebSearch, WebFetch, Task]
---

# Q&A Preparation

You are helping a founder prepare for the toughest questions VCs will ask during their fundraise.

## Input

The user provided: $ARGUMENTS

## Process

### Step 1: Understand the Company

If context is incomplete, ask:
- What does your company do?
- What stage/round are you raising?
- What are your key metrics?
- What do you think your biggest weaknesses are?
- What questions have VCs asked that tripped you up?

### Step 2: Identify Top 10 Tough Questions

Launch the `qa-coach` agent in preparation mode. Instruct it to apply its thinking toolkit: red-team each prepared answer, run a pre-mortem to identify the Q&A moment that would kill the deal, and use inversion to determine which weaknesses to lean into vs. bridge away from. Based on the company's specific situation, identify the 10 toughest questions this founder will face, tailored to:
- Their stage (seed questions differ from Series A)
- Their specific weaknesses
- Their market and competitive dynamics
- Current macro environment

### Step 3: Coach Responses

For each question, present:
1. **The Question**
2. **Why They're Asking** -- The underlying concern
3. **The Trap** -- What a bad answer sounds like
4. **Strong Response** -- Using Acknowledge-Bridge-Message framework
5. **Follow-Up** -- What they'll ask next

### Step 4: Live Simulation (Optional)

Ask the user if they want to practice live. If yes:
- Play the role of a skeptical VC partner
- Ask questions one at a time
- After each answer, provide coaching feedback
- Score responses on a 1-5 scale
- Focus on areas that need improvement

### Step 5: Summary

Provide a cheat sheet:
- The 3 questions you're strongest on
- The 3 questions that need more work
- The #1 question that could kill the deal (from pre-mortem analysis)
- Key phrases to remember
- Red flags to avoid
- Signals to watch for during the live meeting (what to adjust based on VC reactions)
