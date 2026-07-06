# LPIC-3 305 Master Guide

Objective-based training guide for LPIC-3 Exam 305: Virtualization and Containerization.

## Goal

This repository is a study system for passing the LPIC-3 305 certification.

The guide is built one official objective at a time.
The official LPI Exam 305 objectives page is the source of truth for objective text, weights, knowledge areas and listed utilities:

```text
https://www.lpi.org/our-certifications/exam-305-objectives/
```

Version 1.x focuses on exam readiness.
Editorial polish and broader reference material are secondary.

---

## Training Principles

- verify every objective against the official LPI page
- cover every official knowledge area and listed utility
- explain required terminology before using it
- keep the focus on passing LPIC-3 305
- include labs only when they improve understanding
- update `docs/glossary.md` when new exam-relevant terms are introduced
- review each chapter before considering the objective complete

The working agreement defines the project rules:

```text
docs/foundation/working-agreement.md
```

---

## Workflow

Each objective follows this path:

1. Check the official LPI Exam 305 objective.
2. Write or update the chapter using `docs/foundation/chapter_prompt.md`.
3. Add glossary entries for new exam-relevant terms.
4. Add a lab only if it materially improves understanding.
5. Review the chapter using `docs/foundation/review_prompt.md` and `docs/foundation/review_process.md`.
6. Drill the objective using `docs/foundation/exam_drill_prompt.md`.
7. Update `docs/foundation/progress.md`.
8. Close the objective only when no blocking gaps remain and the drill is passed.

The AI assistant acts as trainer and co-author.
The learner reviews, challenges and approves completed objectives.

For the four-week training plan, use:

```text
docs/foundation/study_plan_4_weeks.md
```

---

## Repository Structure

```text
docs/
  foundation/
    working-agreement.md
    chapter_prompt.md
    review_prompt.md
    review_process.md
    exam_drill_prompt.md
    study_plan_4_weeks.md
    progress.md
  351/
    351.1.md
    351.2.md
    351.3.md
  labs/
    lab01-linux-virtualization-stack.md
  glossary.md
```

---

## Definition of Done

An objective is complete when:

- the official objective was reviewed
- all official knowledge areas and listed utilities are covered
- terminology is explained and reflected in the glossary
- required theory, architecture, commands and configuration are documented
- useful labs and knowledge checks are complete
- exam drill is passed
- the chapter has been reviewed
- no blocking issues remain
- both project members approve closure

The full Definition of Done lives in `docs/foundation/working-agreement.md`.

---

## Status

Current Version:

**Version 1.x - Exam Preparation**

Project Status:

In Progress
