---
description: Build a complete fundraising narrative and pitch deck structure from your company information
argument-hint: [description of your company, stage, and what you're raising]
allowed-tools: [Read, Glob, Grep, WebSearch, WebFetch, Task]
---

# Build Fundraising Narrative

You are helping a founder build a complete, compelling fundraising narrative from scratch, following the Sequoia arc and 10-slide structure.

## Input

The user provided: $ARGUMENTS

## Process

### Step 1: Discovery Interview

Conduct a structured interview to extract all raw material. Ask these questions in groups of 3-4 to avoid overwhelming the founder:

**Round 1: The Basics**
- What does your company do in one sentence?
- What specific problem are you solving, and for whom?
- What stage are you raising, and how much?

**Round 2: The Earned Secret**
- What do you see about this market that most people don't?
- How did you arrive at this insight? What specific experiences led you here?
- What would surprise most people about how this problem actually works?

**Round 3: The Market**
- Who is your customer? Describe them specifically.
- How many potential customers exist? What would they pay?
- What do they use today, and why is it inadequate?

**Round 4: The Evidence**
- What's your current traction? (MRR, users, growth rate, retention)
- What's your strongest piece of evidence that this works?
- Tell me about your most enthusiastic customer -- what do they say?

**Round 5: The Team and Ask**
- Why are you and your co-founders the right team for this?
- What will you do with the capital? What milestones will it unlock?
- What's the biggest risk, and how are you mitigating it?

### Step 2: Build the Narrative

Launch the `narrative-architect` agent with all gathered context. Instruct it to apply its thinking toolkit: use first-principles to validate the earned secret, systems thinking to map the problem ecosystem, jobs-to-be-done to frame the VC's decision, and feedback loops to identify the business flywheel. Request:
- Complete narrative arc (Hook, Interest, Consideration, Action)
- 10-slide deck content with headlines, key messages, supporting content, and speaker notes
- The 30-second retell test
- The core flywheel: a description of the reinforcing loop that makes the business increasingly defensible

### Step 3: Present to User

Present the complete narrative:

1. **The Narrative Arc** -- The emotional journey of the pitch
2. **The 10 Slides** -- Slide-by-slide content with specific language
3. **The 30-Second Retell** -- How a VC would describe this to their partners
4. **The Investment Thesis** -- 3-8 bullet points that open slide 1

### Step 4: Refine

Ask the user:
- Does the earned secret feel authentic? Did we capture it correctly?
- Are there metrics or stories we should add or change?
- Does the "why now" resonate with what you're seeing in the market?
- Would you like to stress-test this with a Q&A simulation?
