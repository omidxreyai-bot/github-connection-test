# AI PROJECT ACCESS / MASTER CONTEXT

> Purpose: persistent, compact project context for AI-assisted work.
> This file is a source-of-truth index, not a replacement for detailed project files.
> Updated: 2026-10-01

## 1. WORKING MODE

The assistant should:
- Prefer existing project context over asking the user to repeat information.
- Never invent missing facts.
- Distinguish VERIFIED FACTS, ASSUMPTIONS, CLAIMS, DECISIONS, IDEAS, and COMPLETED OUTPUTS.
- For active projects: FINISH > START.
- Before major project work: check STATUS -> GAP -> PRIORITY -> ACTION -> VERIFICATION.
- Preserve continuity across related conversations when reliable context is available.
- If a required detail is missing, ask only for that detail rather than requesting the entire project history.

## 2. PRIMARY DOMAIN

Main professional field: filmmaking / screenwriting / visual storytelling.

Current project workspace:
- طراحی فیلمنامه و رمان

## 3. ACTIVE / RELEVANT CREATIVE PROJECTS

### 3.1 فیلمنامه «غفلت»
Status: In development / screenplay text is being entered incrementally.
Rule: Do not analyze prematurely when the user is still uploading/entering the script. Wait for the user's signal that the section is complete.

### 3.2 «گناهکار مقدس»
Format: screenplay + short novel concept.
Core setting: remote monastery.
Key characters/concepts: confessor, Mother Superior, Sister Eliane, Brother Cedric.
Core themes under exploration:
- guilt vs responsibility
- personal choice vs institutional rules
- faith, mercy, self-deception
- silence and confession
- moral responsibility without simplistic blame
User wants strong critical evaluation of story/novel potential, not blind agreement.

### 3.3 «سقوط آزاد»
Format: approximately 20-page short novel.
Author: امید عرب.
Core elements:
- Somayeh, audio engineer
- singer Nika Azar
- viral 17-second public clip
- hidden 31-second file labeled “31”
- 11.2 kHz noise
- Hope/Omid edited PUBLIC_17
- journalist Leila Movahed
- Younes and Arman / “گوش دوم” account
- sponsor/producer Farhad
- monitor transmitter power-supply repair before performance
- Nika later says the disputed phrase was from rehearsal
Themes:
media distortion, bystander/supporter control, privacy, responsibility without total blame.

## 4. CREATIVE OUTPUT PREFERENCES

User values:
- professional cinematic thinking
- story logic and dramatic structure
- psychological/behavioral analysis
- visual communication
- practical execution
- critical feedback instead of automatic agreement
- finished deliverables over endless ideation

When analyzing creative work, prioritize:
1. premise
2. dramatic engine
3. character motivation
4. conflict/escalation
5. causality
6. subtext
7. visual storytelling
8. originality
9. audience effect
10. feasibility

## 5. PROJECT STATUS RULE

Never claim a project is completed unless the actual output has been produced.
Never treat an IDEA as a DECISION.
Never treat a CLAIM as VERIFIED FACT without evidence.
If user is still importing material, record status as INGESTING / NOT READY FOR FINAL ANALYSIS.

## 6. CONTINUITY PROTOCOL

When a new conversation references a known project:
1. Identify the project from this index.
2. Load only the relevant project context.
3. Continue from the latest known status.
4. Ask for missing source material only when necessary.
5. Do not dump the entire context into the conversation unless requested.

## 7. IMPORTANT LIMITATION

This GitHub file does NOT automatically become ChatGPT memory.
It is an external source-of-truth that can be fetched when needed.
Its purpose is to reduce repeated manual context transfer, not to remove model/context limits.

## 8. FUTURE STRUCTURE

Recommended repository structure:

/00_CONTEXT/
  MASTER_CONTEXT.md
  PROJECT_INDEX.md
  CHANGELOG.md

/01_SCREENPLAYS/
  /GHAF_LAT/
  /SACRED_SINNER/
  ...

/02_NOVELS/
  /FREE_FALL/
  ...

/03_VISUAL_DESIGN/
  /POSTERS/
  /BRANDING/
  ...

/04_MUSIC/
  /FROM_EARTH_TO_LIGHT/

/05_DECISIONS/
  ADR-*.md

/06_ARCHIVE/

## 9. CHANGE CONTROL

Whenever a major project decision is made, update:
- status
- decision
- rationale
- next action

Do not silently overwrite important decisions.

## 10. MASTER RULE

The assistant should use this file as a navigation layer, then retrieve the smallest relevant source file needed for the current task.

END OF MASTER CONTEXT
