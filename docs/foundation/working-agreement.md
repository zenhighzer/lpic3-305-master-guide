# Working Agreement

**Version:** 1.2  
**Status:** Active  
**Last Updated:** 2026-07-06

> ## Project Governance
>
> This document defines the working agreement for the **LPIC-3 305 Master Guide** project.
>
> Whenever this document conflicts with a previous conversation or earlier design decision, **this document takes precedence**.
>
> Changes to this agreement require explicit approval from both project members.

---

# Purpose

The purpose of this project is **not** to create another LPIC-3 summary.

The goal is to create a technically correct, objective-based, practical and reviewable study guide that prepares the learner for the LPIC-3 305 certification while also serving as a long-term technical reference.

Version **1.x** of this project focuses on passing the LPIC-3 305 exam.

Editorial improvements, additional background information and community-oriented enhancements are intentionally deferred to **Version 2.0**.

---

# Project Roles

## Author (ChatGPT)

Responsible for:

- explaining technical concepts
- maintaining objective alignment
- ensuring technical correctness
- providing reviewable documentation
- identifying exam-relevant topics
- admitting and correcting mistakes

## Reviewer (You)

Responsible for:

- reviewing technical correctness
- questioning assumptions
- validating explanations
- maintaining exam focus
- identifying unclear explanations
- approving completed objectives

---

# Guiding Principles

## 1. Objective First

Every technical statement must first be validated against the **official LPIC-3 305 objectives**.

No assumptions.

No "this is probably part of the exam."

---

## 2. Official Source Wins

Whenever there is a conflict between this guide and an official source, the official source always takes precedence.

Examples include:

- LPIC-3 Objectives
- Official product documentation
- Official manuals
- Standards

The guide must be corrected accordingly.

Never modify the official meaning to fit the guide.

Always modify the guide to fit the official source.

---

## 3. Source Separation

Every statement belongs to exactly one category.

- Official Objective
- Explanation
- Background
- Exam Tip

Readers must always be able to distinguish between official exam requirements and additional explanations.

---

## 4. If Unsure → Verify

Whenever uncertainty exists regarding an exam-relevant topic, the information must be verified before it is documented.

Guessing is not acceptable.

---

## 5. No Hallucinations

Exam-relevant facts must never be invented, assumed or completed from memory if reliable verification is possible.

Accuracy is always preferred over speed.

---

# Repository Rules

## 6. Structure Freeze

After Sprint 0 the repository structure is frozen.

Structural changes are only allowed if:

- an actual mistake has been identified
- the official objectives require a change
- both project members explicitly agree

Repository stability is preferred over continuous restructuring.

---

## 7. Single Source of Truth

Every piece of information should exist in exactly one location.

Avoid duplicate documentation whenever possible.

---

## 8. Incremental Development

Each commit should introduce one meaningful improvement.

Avoid mixing unrelated topics within the same commit.

---

## 9. Repository State

At the beginning of each working session, the current Git commit hash should be provided.

All discussions, reviews and changes refer to this repository state.

The Git repository is the single source of truth for project files.

The author must only claim repository synchronization when the current repository state has actually been verified.

If repository access is unavailable or unreliable, the latest provided commit hash or file content is used as the temporary working state.

---

# Writing Rules

## 10. One Objective at a Time

Only one LPIC objective is worked on at any given time.

A new objective starts only after the previous one has been completed and reviewed.

---

## 11. Existing Knowledge First

Whenever possible, new concepts should be explained using knowledge that is already familiar to the learner.

Examples include:

- Proxmox VE
- Docker
- VMware
- Linux
- DevOps

---

## 12. No Silent Assumptions

Technical terms must be introduced before they are used.

Do not assume previous knowledge without explanation.

---

## 13. 80/20 Principle

Focus first on the knowledge that provides the highest value for passing the exam.

Deep dives are welcome but must be clearly identified as additional information.

---

## 14. Exam First

The primary goal of Version **1.x** is to pass the LPIC-3 305 certification within the planned time frame.

Whenever there is a trade-off between editorial perfection and exam preparation, **exam preparation always takes precedence**.

Improvements that do not significantly increase the likelihood of passing the exam are deferred to Version **2.0**.

---

## 15. Labs only when Useful

Hands-on labs are included only if they significantly improve understanding.

Not every objective requires a practical lab.

---

# Review Process

## 16. Challenge Everything

Every technical statement may be questioned.

Critical review improves the quality of the guide.

Disagreement is part of the review process.

---

## 17. Transparency

Whenever information is based on interpretation, experience or best practices rather than the official objectives, this must be clearly indicated.

Readers should always know whether a statement is:

- an official requirement
- a technical explanation
- an exam tip
- a recommendation
- practical experience

---

## 18. Admit Mistakes

Mistakes are corrected openly.

There is no attempt to justify incorrect information.

Accuracy is more important than ego.

---

## 19. Review before Complete

An objective is considered complete only after both project members agree that it satisfies the defined quality standards.

---

## 20. Single Review Cycle

Each review consists of one complete review pass.

All requested changes must be communicated together.

Subsequent review rounds are limited to verifying previously requested changes.

New review comments may only be introduced if:

- a factual error was previously overlooked
- a requested change introduced a new issue

---

# Project Philosophy

## 21. Quality over Speed

The goal is not to finish quickly.

The goal is to maximize the probability of passing the LPIC-3 305 certification while producing a technically correct study guide.

Editorial perfection is intentionally postponed to Version **2.0**.

---

## 22. Focus

Avoid unnecessary discussions about repository structure, tooling or implementation details.

The primary objective is learning LPIC-3 305.

Whenever focus is lost, immediately return to the current objective.

Questions that are interesting but not exam-relevant should be recorded as ideas for Version **2.0**, not implemented immediately.

---

# Definition of Done

An objective is considered complete when:

- [ ] Official objective reviewed
- [ ] Official knowledge areas covered
- [ ] Required terminology explained
- [ ] Theory completed
- [ ] Architecture explained (if applicable)
- [ ] Commands documented (if applicable)
- [ ] Configuration documented (if applicable)
- [ ] Related lab completed (if applicable)
- [ ] Knowledge check completed
- [ ] Summary written
- [ ] Chapter reviewed
- [ ] No blocking issues remain
- [ ] Approved by both project members

---

# Success Criteria

Version **1.x** is considered successful when:

- every official LPIC-3 305 objective has been covered
- every chapter has been reviewed
- all identified knowledge gaps have been closed
- the learner understands the concepts instead of memorizing answers
- the learner passes the LPIC-3 305 certification

Version **2.0** may improve style, diagrams, additional labs, wording and community-oriented documentation without changing the technical correctness established in Version **1.x**.