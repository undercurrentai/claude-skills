# legal-voice

A Claude Code skill that produces legal writing indistinguishable from work drafted by an experienced attorney. Clear, precise, authoritative, and free of AI tells.

## What It Does

When activated, this skill applies a comprehensive legal writing voice to any content Claude generates. The voice is derived from the collected wisdom of Bryan Garner, Ross Guberman, Joseph Kimble, Richard Wydick, Justice Scalia, Kenneth Adams, and 30+ additional legal writing authorities.

The skill covers seven document types with distinct voice calibrations:

| Document Type | Voice Mode |
|---------------|------------|
| Briefs and Motions | Persuasive advocacy |
| Legal Memoranda | Objective analysis |
| Contracts | Operational precision |
| Demand Letters | Firm professionalism |
| Client Communications | Accessible authority |
| Appellate Briefs | Scholarly restraint |
| Complaints/Pleadings | Factual assertion |

## Key Features

- **Full LLM-ism ban lists**: Research-backed word and phrase bans (Kobak et al. 2025, Liang et al. 2024) plus legal-specific extensions (archaic legalese, redundant doublets, throat-clearing phrases)
- **Analytical frameworks**: IRAC, CRAC, CREAC with guidance on when to use each
- **Persuasion techniques**: Theory of the case, strategic fact framing, counterargument handling, primacy/recency
- **Language rules**: Plain English, active voice, conciseness, Oxford comma, modern modal verbs (must/may, not shall)
- **Anti-patterns**: 15 explicit prohibitions drawn from Garner's and Guberman's collected faults

## Installation

Copy the plugin directory to your Claude Code plugins path:

```bash
cp -r legal-voice/ ~/.claude/plugins/legal-voice/
```

Or install from the skills repository:

```bash
claude plugin add legal-voice
```

## Usage

The skill triggers when you ask Claude to draft, review, or improve legal documents. Trigger phrases include:

- "Draft a motion for..."
- "Write a legal memo analyzing..."
- "Draft contract language for..."
- "Write a demand letter..."
- "Review this brief for legal writing quality"
- "Apply legal voice to..."

## Authorities

This skill synthesizes guidance from:

- Bryan A. Garner: *Legal Writing in Plain English* (3rd ed. 2024), *The Winning Brief*, *The Elements of Legal Style*, *Making Your Case* (with Justice Scalia)
- Ross Guberman: *Point Made* (2nd ed. 2014), *Point Taken* (2015), BriefCatch
- Joseph Kimble: *Lifting the Fog of Legalese* (2006), Michigan Bar Journal plain language columns
- Richard Wydick & Amy Sloan: *Plain English for Lawyers* (7th ed. 2024)
- Kenneth A. Adams: *A Manual of Style for Contract Drafting* (5th ed. 2023)
- Columbia Law School Writing Center, Georgetown Law Writing Center, ABA Appellate Practice
