# Systemic Investing Design — a Claude Skill

A Claude skill for designing **the financing of systems transformation**: strategies, portfolios, and vehicles that deploy capital to transform human and natural systems — rather than pipelines of individually impressive deals. It is the capital-side complement to the [regenerative-business-design](https://github.com/jagypus/regenerative-business-design) skill: one designs the venture worth funding, the other designs the funding worth having.

It weaves together:

- **The TransCap Initiative** (Dominic Hofstetter and colleagues) — the systemic investing paradigm: the system→capital reversal, strategic multi-asset portfolios nested in broader intervention strategies, combinatorial "1+1=3" effects, financial backbones, and systemic intelligence
- **TWIST** (Together We Invest for Systems Transformation) — the wealth-holder journey: levers beyond the portfolio (voice, networks, political capital), peer learning, and the inner shift from "what return does my impact make" to "what does the system need from me"
- **The Investor's Guide to Systemic Investing** (CSP/UZH, MIT Sloan, TransCap, The ImPact, TWIST) — the consensus getting-started articulation across the field's five networks
- **TIIP / Burckart & Lydenberg** (*21st Century Investing*) — the adjacent system-level investing lineage for institutional fiduciaries, kept precisely distinct
- **Tamarack Institute** (Cabaj, Wellsch & Perla, *There is No Such Thing as a "Fish"*) — the portfolio typology (Cabinet of Curiosities, System Probes, Stage Gate, Strategic Gaps, Risk-Reward, Synergy, hybrids), the fit test, and the per-archetype evaluation questions
- **Donella Meadows** — leverage points and the systems-thinking substrate
- **Kania, Kramer & Senge** (*The Water of Systems Change*) — the six conditions an intervention portfolio must touch
- **Catalytic & blended capital practice** (MacArthur C3, Tideline, Convergence) — first-loss, guarantees, tranching, and the crowding-in discipline
- **Michael Quinn Patton** — *Developmental Evaluation*, *Principles-Focused Evaluation*, and **Blue Marble Evaluation**: evaluating transformation by transformation criteria, with learning embedded in the strategy team

The skill runs in three modes: a Socratic **design dialogue** for allocators, a written **strategy blueprint** deliverable, and a **diagnostic** for existing portfolios (which begins by naming which kind of portfolio you actually have — often a Cabinet of Curiosities that believes itself a Synergy portfolio). It is deliberately non-evangelical: every recommendation carries its honest price tag (coordination overhead, decade-plus horizons, attribution friction, thin track record), and it states plainly when conventional impact investing or plain grantmaking is the better choice.

## Install

**Claude Code** — point Claude at this repo and it installs itself:

```
/plugin marketplace add jagypus/systemic-investing-design
/plugin install systemic-investing-design@systemic-investing-design
```

Or with the skills CLI:

```
npx skills add jagypus/systemic-investing-design
```

**Claude Desktop / Cowork** — add this repo's GitHub URL as a plugin marketplace in Settings → Capabilities, or download `systemic-investing-design.skill` from this repo (or the latest Release) and install it from the chat.

**Manual** — copy `skills/systemic-investing-design/` into your `~/.claude/skills/` directory.

## Usage

Just talk to Claude about your capital. Examples:

- "Our family office has set aside €25M 'for systems change' in the regional food system. Where do we even start? Design us a strategy."
- "Our foundation runs a £40M impact portfolio and the board says we do 'systemic investing'. Do we? Be honest."
- "I'm structuring a blended finance vehicle for water resilience with a development bank senior tranche — how do I stop it becoming just a deal fund?"

## Structure

```
skills/systemic-investing-design/
├── SKILL.md                          # orchestrator: stance, five-layer design stack, three modes
├── evals/evals.json                  # benchmark test cases with assertions
└── references/
    ├── paradigm.md                   # lineage map, wealth-holder journey, positionality, metaphor tension
    ├── system-understanding.md       # boundary choice, mapping, leverage points, sensemaking
    ├── theory-of-transformation.md   # combinatorial thesis, Tamarack portfolio typology, partner ecology
    ├── capital-architecture.md       # capital spectrum, vehicle geometry, backbones, honest downside ledger
    └── learning-measurement.md       # developmental evaluation, Blue Marble, three-altitude indicators
```

## Caveats

This skill provides design thinking, not legal, tax, or investment advice. Fiduciary duty, foundation law, and the regulatory treatment of blended structures vary by jurisdiction — implement with qualified counsel and advisors. The field is young and moves fast; the skill is instructed to verify live actors, vehicles, and evidence on the web rather than asserting from its reference files.

## License

MIT
