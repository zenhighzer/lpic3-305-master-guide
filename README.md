# LPIC-3 305 Master Guide

Objective-based study guide for LPIC-3 Exam 305: Virtualization and Containerization.

## What Is This?

This repository is a study system for passing the LPIC-3 305 certification.

The guide is built one official objective at a time.
The official LPI Exam 305 objectives page is the source of truth for objective text, weights, knowledge areas and listed utilities:

```text
https://www.lpi.org/our-certifications/exam-305-objectives/
```

Version 1.x focuses on exam readiness.
Editorial polish and broader reference material are secondary.

---

## Who Is It For?

This project is for a learner preparing for LPIC-3 305 who wants:

- objective-based study chapters
- practical Linux virtualization and containerization explanations
- exam-focused labs where they add value
- glossary support for important terms
- a clear path from learning to review to exam drills

---

## Where Do I Start?

Start with:

1. `docs/351/351.1.md`
2. `docs/foundation/study_plan_4_weeks.md`
3. `docs/foundation/progress.md`

The recommended learning order is the official objective order:

1. `351.1` Virtualization Concepts and Theory
2. `351.2` Xen
3. `351.3` QEMU
4. `351.4` Libvirt Virtual Machine Management
5. `351.5` Virtual Machine Disk Image Management
6. `352.x` Container Virtualization
7. `353.x` Cloud Management Tools

---

## Repository Structure

```text
docs/
  foundation/
  351/
  labs/
  glossary.md
```

---

## Study Method

For each objective:

1. Read the chapter.
2. Learn the listed commands, files and terms.
3. Do the lab if one exists.
4. Answer the knowledge check.
5. Drill the topic until you can explain it without notes.
6. Update progress.

---

## Project Rules

The project rules live in `docs/foundation/working-agreement.md`.

The short version:

- official LPI objectives win
- exam readiness comes first
- one objective at a time
- no local copy of the official objective text
- update the glossary for new exam-relevant terms
- close an objective only after review and drill

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
