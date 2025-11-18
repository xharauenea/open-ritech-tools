# Presenter Notes Design for Open Ritech Tools Slides

**Date:** 2025-11-19
**Purpose:** Add brief presenter notes to slides.md to keep speakers on track during presentations

## Context

The slides.md file contains a Slidev presentation covering 5 Open Ritech tools:
- TechDebtGPT (SaaS platform)
- CodeWave (commit analysis)
- MainSight (maintenance prediction)
- ArchDoc Generator (architecture docs)
- PR Agent (pull request analysis)

## Requirements

- Notes for someone else presenting (not the creator)
- Brief reminders to prevent wandering
- Include use cases for context
- Content guidance only (no timing)
- Should not be visible during presentation

## Design Decision

**Format:** Inline HTML comments placed after slide content, before slide separators (`---`)

**Rationale:**
- Simple and stays with slide content
- Invisible in presentation view
- Easy to scan while editing
- No special Slidev configuration needed

## Notes Structure

Each note follows this pattern:
```markdown
<!--
[Key point or emphasis]
[Use case or example]
-->
```

### Content Guidelines by Slide Type

1. **Opening slides**: Set tone and expectations
2. **Tool overview**: Remind to pace through v-click animations
3. **Tool intro slides**: One-line value proposition
4. **"Why?" slides**: 1-2 practical use cases + key talking point
5. **Final CTA slide**: Emphasize call to action

### Example Note Formats

**Title slide:**
```markdown
<!-- Welcome tone: Emphasize "open to everyone" - these are free, open-source tools -->
```

**Feature slide:**
```markdown
<!--
Key point: "Without changing workflow" - no code access needed
Use case: Team adopted in 2 days, discovered 40% of PRs blocked by single reviewer
-->
```

**Benefit slide:**
```markdown
<!--
Emphasize: 8 specialized agents working together
Use case: New developer onboarded by reading generated docs instead of 2-week code review
-->
```

## Implementation Plan

For each of the 11 slides, add HTML comments with:
- Slide 1 (Open Ritech): Welcome tone
- Slide 2 (Our Tools): Pacing reminder for v-clicks
- Slides 3-4 (TechDebtGPT): Value prop + use case
- Slides 5-6 (CodeWave): Value prop + use case
- Slides 7-8 (MainSight): Value prop + use case
- Slides 9-10 (ArchDoc): Value prop + use case
- Slides 11-12 (PR Agent): Value prop + use case
- Slide 13 (Try Them Out): Call to action emphasis

## Success Criteria

- Each slide has 1-2 line note
- Notes include concrete use cases where relevant
- Comments are brief enough to scan quickly
- Content guides "what to emphasize" not "what to say"
