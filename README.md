# Claude Code VC Fundraising Toolkit

Comprehensive VC fundraising and investor relations toolkit for CEOs, powered by first principles from Sequoia, a16z, Benchmark, YC, and enhanced with structured thinking frameworks.

## Features

- **5 Specialized Agents** -- Pitch analysis, narrative architecture, Q&A coaching, fundraise strategy, investor updates
- **6 Commands** -- One-command workflows for common fundraising tasks
- **2 Domain Skills** -- Deep knowledge bases for narrative construction and investor relations
- **Thinking-Enhanced** -- Integrates with [cc-thinking-skills](https://github.com/tjboudreaux/cc-thinking-skills) for systems thinking, first-principles analysis, red-teaming, and more
- **First-Principles Grounded** -- Built on proven frameworks from Sequoia, a16z, Benchmark, Floodgate, NFX, and YC

## Prerequisites

This plugin works standalone, but is enhanced by the [Claude Code Thinking Skills](https://github.com/tjboudreaux/cc-thinking-skills) plugin. Installing thinking-skills unlocks deeper analytical capabilities across all agents -- including first-principles decomposition, systems thinking, red-teaming, feedback loop analysis, and more.

```bash
# Install thinking-skills (recommended)
claude plugin add /path/to/cc-thinking-skills
```

## Installation

```bash
# Clone and add as a plugin
git clone https://github.com/tjboudreaux/cc-skills-vc-fundraising.git
claude plugin add /path/to/cc-skills-vc-fundraising

# Or during development
claude --plugin-dir ./cc-skills-vc-fundraising
```

## Commands

| Command | Description |
|---------|-------------|
| `/pitch-review` | Review and score a pitch deck against VC first principles (11 dimensions, scored out of 55) |
| `/build-narrative` | Build a complete pitch narrative and 10-slide deck from company information |
| `/qa-prep` | Prepare for tough VC Q&A with coached responses and optional live simulation |
| `/fundraise-plan` | Plan your fundraising process end-to-end with timeline, target list, and competitive dynamics |
| `/investor-update` | Draft a monthly investor update in the 5-15 format |
| `/board-deck` | Build a board meeting deck following the Sequoia 3-hour framework |

## Agents

| Agent | Model | Description | Thinking Enhancements |
|-------|-------|-------------|----------------------|
| `pitch-analyst` | Opus | Evaluates pitches across 11 dimensions | First principles, red-team, inversion, steel-manning, map-territory |
| `narrative-architect` | Opus | Builds complete pitch narratives | First principles, systems, JTBD, second-order, feedback loops, leverage points |
| `qa-coach` | Opus | Prepares founders for tough Q&A | Red-team, inversion, steel-manning, pre-mortem, bayesian updating |
| `fundraise-strategist` | Sonnet | Plans end-to-end fundraising process | Systems, feedback loops, theory of constraints, pre-mortem, second-order, OODA, regret minimization |
| `investor-update-writer` | Sonnet | Drafts investor communications | Feedback loops, inversion, systems, second-order |

## Skills

| Skill | Auto-Activates On |
|-------|-------------------|
| `fundraising-narrative` | "pitch deck", "fundraising story", "VC narrative", "earned secret", "why now", "TAM SAM SOM", etc. |
| `investor-relations` | "investor update", "board deck", "monthly update", "bad news investors", "warm intro", etc. |

## How Thinking Skills Are Integrated

Each agent has two tiers of thinking framework integration:

**Primary lenses** (always applied) -- 1-2 frameworks woven directly into the agent's existing process steps. These are the frameworks that most naturally align with what the agent does:
- The pitch-analyst always applies first-principles decomposition to earned secrets and red-teams the overall pitch
- The narrative-architect always uses systems thinking to map the problem ecosystem
- The qa-coach always red-teams every prepared answer

**Thinking Toolkit** (applied situationally) -- 2-6 additional frameworks available when deeper analysis is needed. Each toolkit entry includes a domain-specific prompt that translates the abstract framework into VC fundraising action. The agent selects from these based on the specific situation rather than applying them all every time.

This tiered approach prevents analysis bloat while ensuring the most impactful frameworks are always applied.

## The 10 First Principles

The entire toolkit is grounded in these first principles (see [FIRST_PRINCIPLES.md](FIRST_PRINCIPLES.md) for the complete framework):

1. **Story IS Strategy** -- The narrative is the business case
2. **Lead with the Earned Secret** -- Non-obvious insight earned through experience
3. **"Why Now" Is the Linchpin** -- Specific inflection point, not gradual trend
4. **Prove Value Before Growth** -- Desperate customers before scaling claims
5. **The Customer Is the Hero** -- You're the mentor, not the protagonist
6. **Market Size: Ambitious + Defensible** -- Bottom-up credibility, top-down ambition
7. **Clarity Over Polish** -- Heading test, plain language, no qualifiers
8. **Numbers in Every Sentence** -- Metrics replace adjectives
9. **Design for Internal Championing** -- Optimize for the IC meeting you don't attend
10. **Fundraising Is Continuous** -- Lines, not dots

## License

MIT License -- see [LICENSE](LICENSE) for details.

## Author

Created by [Travis Boudreaux](https://github.com/tjboudreaux)
