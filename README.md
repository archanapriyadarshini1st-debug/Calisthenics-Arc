# Calisthenics Arc 🥋

Calisthenics Arc is a personal workout journal and progression system built to let ChatGPT act as a long-term calisthenics mentor.

## Why we created this

Instead of generating random workouts, this repo keeps a persistent history of training sessions. Each session records what was trained, how much was completed, and when the workout happened. Future workouts can then be adjusted from the previous training history.

The progression loop is:

**Train → Log → Analyze → Progress → Train again**

The goal is steady improvement in strength, control, skills, and exercise difficulty without relying on unnecessary volume.

## Mentor trigger

Use this exact phrase when starting a new session:

> **Mentor, today's workout.**

When that phrase is used, the mentor should review the previous workout logs before recommending the next session. The previous performance should influence exercise choice, reps, sets, tempo, difficulty, and progression.

## Workout log format

Every workout should include:

- Day number
- Exact date
- Time of day: Morning / Afternoon / Evening / Night
- Exercise list
- Sets and reps or hold time
- Difficulty/effort when available
- Notes and progression decisions

## Time-of-day tracking

Workout timing is intentionally logged as a broad period rather than requiring an exact clock time:

`Morning` · `Afternoon` · `Evening` · `Night`

## Progression rules

The mentor should prefer gradual progression based on demonstrated performance. Possible progressions include adding a small number of reps, adding a set when appropriate, slowing the tempo, increasing range of motion, improving technique, or moving to a harder variation.

Recovery matters. A workout should not automatically become harder every day; fatigue, soreness, technique quality, and recent training history should influence progression.

## Exercise library and research

- [Exercise catalogue](./exercise-catalogue.md) — controlled bodyweight movements and meaningful variations, grouped by movement pattern.
- [Research and coverage audit](./exercise-research-audit.md) — sources, ten coverage checks, scope limits, and update procedure.

The catalogue is a reference index, not a workout prescription or an exhaustive list of every exercise published online. High-risk acrobatic and extreme-leverage skills are intentionally excluded.

## Directory structure

```text
workouts/
  YYYY-MM-DD.md
progression/
  push.md
  legs.md
  core.md
  skills.md
stats.md
```

This repository is the source of truth for the workout history used by the mentor.
