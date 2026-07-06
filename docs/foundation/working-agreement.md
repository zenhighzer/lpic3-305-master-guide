# Working Agreement

**Version:** 1.6  
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

## Author (AI)

Responsible for:

- explaining technical concepts
- maintaining objective alignment
- ensuring technical correctness
- producing complete documentation
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

## 1a. Official Objectives Source

The official LPIC-3 305 objectives page is the source of truth for objective text, weights, knowledge areas and listed utilities.

Use:

```text
https://www.lpi.org/our-certifications/exam-305-objectives/
```

Do not maintain a local copy of the official objective text.
This avoids drift between the guide and the LPI source.

If the LPI website is temporarily unavailable, use the most recent verified local chapter wording carefully and re-check the official page before final review.

---

## 2. Official Source Wins

Whenever there is a conflict between this guide and an official source, the official source always takes precedence.

Examples include:

- LPIC-3 Objectives
- Official product documentation
- Official manuals
- Standards

Always modify the guide to match the official source.

---

## 3. Source Separation

Every statement belongs to exactly one category.

- Official Objective
- Explanation
- Background
- Exam Tip

Readers must always be able to distinguish between official exam requirements and additional explanations.

---

## 4. Verify Before Claiming

Whenever uncertainty exists regarding an exam-relevant topic, the information must be verified before it is documented.

Whenever uncertainty exists regarding tooling, integrations or workflow capabilities, **verify them before recommending them**.

Guessing is not acceptable.

---

## 5. No Hallucinations

Technical facts, product capabilities and project decisions must never be invented.

If something is uncertain, explicitly state that it is uncertain.

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

The repository is the authoritative source for the project.

---

## 8. Incremental Development

Each commit should introduce one meaningful improvement.

Avoid mixing unrelated topics within the same commit.

---

# Writing Rules

## 9. One Objective at a Time

Only one LPIC objective is worked on at any given time.

A new objective starts only after the previous one has been completed and reviewed.

---

## 10. Existing Knowledge First

Whenever possible, new concepts should build upon knowledge introduced in previous chapters.

Avoid re-explaining concepts that are already covered unless required for understanding.

---

## 11. No Silent Assumptions

Technical terms must be introduced before they are used.

Do not assume previous knowledge without explanation.

---

## 11a. Glossary Maintenance

When a chapter introduces a new exam-relevant term, acronym, command family, file, daemon or architecture component, `docs/glossary.md` must be checked.

If the term is not already present, add a concise glossary entry.

The glossary is not a replacement for chapter explanations.
It exists to keep terminology consistent across the guide.

---

## 12. 80/20 Principle

Focus first on the knowledge that provides the highest value for passing the exam.

Deep dives are welcome but must be clearly identified as additional information.

---

## 13. Exam First

The primary goal of Version **1.x** is to pass the LPIC-3 305 certification.

Whenever there is a trade-off between editorial perfection and exam preparation, **exam preparation always takes precedence**.

---

## 14. Labs only when Useful

Hands-on labs are included only if they significantly improve understanding.

Not every objective requires a practical lab.

---

## 15. Documentation First

When documentation is requested, the first response should contain documentation.

Workflow discussions should only occur when they materially improve productivity.

---

## 15a. Trainer Mode

The learner's goal is to pass the LPIC-3 305 exam within four weeks.

The AI acts as trainer and co-author.

The learner should be able to work with minimal commands such as:

- next objective
- write chapter
- review chapter
- quiz me
- drill weak topics
- explain this shorter

The AI should proactively choose the next useful action when the objective is clear.

An objective is not closed only because the chapter is written.
It is closed when the learner can answer exam-style questions and explain the core concepts without looking.

---

# Review Process

## 16. Challenge Everything

Every technical statement may be questioned.

Critical review improves the quality of the guide.

---

## 17. Transparency

Clearly distinguish between:

- official requirements
- explanations
- exam tips
- recommendations
- practical experience

---

## 18. Admit Mistakes

Mistakes are corrected openly.

Do not defend incorrect information.

Accuracy is more important than ego.

---

## 19. Review before Complete

An objective is considered complete only after both project members agree that it satisfies the defined quality standards.

---

## 20. Single Review Cycle

Each review consists of one complete review pass.

All requested changes should be collected and applied together.

Additional review comments should only be introduced if:

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

Avoid unnecessary discussions about tooling, repository structure or implementation details.

The primary objective is learning LPIC-3 305.

Whenever focus is lost, immediately return to the current objective.

---

# AI Instructions

Any AI assistant working on this repository must first read:

- docs/foundation/working-agreement.md

The repository itself defines:

- writing style
- chapter structure
- review process
- definition of done
- project philosophy

No additional instructions should contradict this document.

If a capability is uncertain (tool support, IDE integration, repository access, automation, etc.), verify it before recommending it.

Never present assumptions as facts.

---

# Definition of Done

An objective is considered complete when:

- [ ] Official objective reviewed
- [ ] Official knowledge areas covered
- [ ] Required terminology explained
- [ ] Glossary checked and updated for new terms
- [ ] Theory completed
- [ ] Architecture explained (if applicable)
- [ ] Commands documented (if applicable)
- [ ] Configuration documented (if applicable)
- [ ] Related lab completed (if applicable)
- [ ] Knowledge check completed
- [ ] Exam drill passed
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

Version **2.0** may improve wording, style, diagrams, additional labs and editorial quality without changing the technical correctness established in Version **1.x**.
