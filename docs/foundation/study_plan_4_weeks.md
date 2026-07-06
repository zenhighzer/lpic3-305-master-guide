# Four-Week LPIC-3 305 Study Plan

This plan is optimized for passing LPIC-3 305 in four weeks.

The official LPI Exam 305 objectives page remains the source of truth:

```text
https://www.lpi.org/our-certifications/exam-305-objectives/
```

Use this plan as a training schedule, not as a replacement for the official objectives.

---

# Daily Loop

For each study session:

1. Read or review one objective chapter.
2. Learn the commands, files and terms listed in that chapter.
3. Do the lab only if it helps understanding.
4. Run an exam drill.
5. Record status in `docs/foundation/progress.md`.
6. Repeat missed questions later.

The target is not to finish pages.
The target is to answer objective-based questions correctly.

---

# Week 1 - Virtualization Foundations

Goal: understand the Linux virtualization stack well enough to reason about hypervisors, Xen and QEMU.

Focus:

- 351.1
- 351.2
- 351.3

Trainer tasks:

- explain virtualization terminology without notes
- compare Xen, QEMU, KVM and libvirt
- recognize required commands and files
- complete the Linux virtualization stack lab
- pass drills for 351.1, 351.2 and 351.3

Exit check:

- explain HVM, PV, emulation, KVM and migration
- explain Dom0 and DomU
- start reading a QEMU command line without freezing

---

# Week 2 - libvirt and VM Disk Images

Goal: manage virtual machines through libvirt and understand virtual disk image workflows.

Focus:

- 351.4
- 351.5

Trainer tasks:

- write and review both chapters
- drill `virsh`, libvirt storage, libvirt networking and XML concepts
- drill `qemu-img` and libguestfs tools
- practice scenario questions around snapshots, migration and disk conversion

Exit check:

- choose the correct libvirt tool or file for a task
- explain storage pools, volumes and virtual networks
- distinguish raw, qcow2, VMDK and OVF at exam level

---

# Week 3 - Containers

Goal: build strong command and concept recognition for containers.

Focus:

- 352.1
- 352.2
- 352.3
- 352.4

Trainer tasks:

- learn namespaces, cgroups, capabilities, seccomp and MAC
- drill LXC/LXD architecture and commands
- drill Docker architecture, images, volumes, networking, logging and Dockerfiles
- compare Docker Compose, Docker Swarm, Kubernetes and Helm at concept level

Exit check:

- map container features to kernel mechanisms
- explain when a term belongs to Docker, LXC/LXD or orchestration
- answer command-recognition questions quickly

---

# Week 4 - Cloud Tools and Final Review

Goal: close remaining objectives and convert weak spots into exam readiness.

Focus:

- 353.1
- 353.2
- 353.3
- 353.4
- full review

Trainer tasks:

- cover cloud management tools, Packer, cloud-init and Vagrant
- run cumulative drills across all objectives
- revisit every missed question
- do short explanation drills for weak topics
- review glossary terms

Exit check:

- answer mixed objective questions without chapter hints
- recognize tools, files and commands under time pressure
- explain the difference between similar technologies
- mark remaining weak topics explicitly

---

# Final Three Days

Use the final days for review, not new deep dives.

Day 1:

- re-drill all failed questions
- review command and file tables
- revisit labs only where they clarify weak concepts

Day 2:

- run mixed drills
- explain each objective in plain language
- review glossary

Day 3:

- light review only
- focus on confidence and recall
- avoid large new topics

---

# Commands for the Learner

Use short commands with the trainer:

- `next objective`
- `write chapter`
- `review chapter`
- `quiz me on 351.3`
- `drill weak topics`
- `explain this shorter`
- `what do I need to know for the exam?`
- `close this objective`
