# Mirror — Deep Astrological Reading as Self-Confrontation

A Claude Code plugin that transforms AI astrology from generic horoscope columns into genuine psychological mirrors. Mirror conducts multi-phase readings that blend natal chart analysis, real-time transits, and conversational psychology to create the "yes, this is me" feeling that most AI readings miss.

## What This Does

Most AI astrology reads like a textbook — it lists transits, explains aspects, and the person feels nothing. Mirror operates on different principles:

- **Being seen** — Articulates something about the person they couldn't articulate themselves
- **Permission** — Reframes a trait they've been ashamed of as part of their design
- **Temporal hope** — Frames difficulty as a phase with an ending
- **Agency** — Leaves them with questions, not predictions

## The 9-Phase Methodology

1. **Gather birth data** (date, time, place)
2. **Build chart + transits** (parallel agents for natal chart and current sky)
3. **Map transits to natal chart** (sect, dispositor tree, nodal story, Chiron profile)
4. **Synthesize into one story** (not a list of transits — one narrative)
5. **Deliver initial reading** (4-5 paragraphs, shadow included, deliberately 70% accurate)
6. **The conversation** (OARS framework, depth tracking, convergence)
7. **Deep dives** (1-2 key placements, extended metaphor, the wound and the gift)
8. **Timing** (real windows, event-level, always paired with agency)
9. **Closing** (grounding, not summarizing)

## Technical Features

- **Sect-aware** — Day vs night chart changes interpretation of Jupiter, Venus, Saturn, Mars
- **Dispositor trees** — Traces hidden power structure of the psyche
- **Three-layer Chiron** — Sign (flavor) + house (domain) + aspects (mechanism)
- **Aspect-modified placements** — No planet described by sign/house alone
- **Combustion/cazimi detection** — Blind spots vs identity fusion
- **Fixed star integration** — Major stars within 1.5 degrees of luminaries/angles
- **Annual profections + zodiacal releasing** — Time-lord techniques for chapter framing
- **OARS conversational framework** — Open questions, Affirmations, Reflections, Summaries

## Install

```bash
claude /plugin install avyanshkatiyar/mirror
```

Or test locally:

```bash
claude --plugin-dir ./mirror-plugin
```

## Usage

In Claude Code:

```
/mirror
```

The skill will ask for birth data and guide the entire reading interactively.

## What This Is NOT

- Not a horoscope generator
- Not a transit list printer
- Not a therapist (names patterns, doesn't diagnose)
- Not a prediction machine (conditions and questions, not prophecies)

## License

MIT
