# Lab 01 – Linux Virtualization Stack

## Purpose

This laboratory environment is used throughout the LPIC-3 305 Master Guide.

All practical examples should use this environment unless a chapter explicitly requires something different.

The goal is consistency across all objectives.

---

# Host System

Operating System

Ubuntu Server 24.04 LTS

Architecture

x86_64

Virtualization Extensions

Intel VT-x or AMD-V enabled

Nested Virtualization

Enabled

Memory

At least 16 GB RAM

Recommended: 32 GB

CPU

4+ cores

Recommended: 8+

Storage

SSD

Minimum 100 GB free

---

# Hypervisors

Primary

KVM

Additional

- Xen
- QEMU
- libvirt

---

# Virtual Machines

Use meaningful names.

Examples

xen01
qemu01
libvirt01
docker01

---

# Networking

Default

Bridged networking

Additional

NAT when Internet access is sufficient.

Avoid custom network topologies unless required by the objective.

---

# Storage

Use separate virtual disks whenever storage management is demonstrated.

Preferred filesystem

ext4

---

# User Accounts

Administrative user

student

Administrative privileges

sudo

Avoid running commands directly as root unless required.

---

# Package Management

Debian / Ubuntu

apt

When distribution-specific commands differ, clearly state the differences.

---

# Naming Conventions

Hosts

lowercase

VM names

technology + number

Examples

xen01

docker02

libvirt01

---

# Command Style

Always use

```bash
sudo command
```

unless root privileges are already assumed.

Use long command options where they improve readability.

---

# Labs

Every lab should include

- Goal
- Prerequisites
- Steps
- Verification
- Cleanup (if applicable)

---

# AI Rules

When generating labs:

- Reuse this environment.
- Do not invent different host names.
- Do not invent different Linux distributions unless required.
- Keep all labs compatible with previous chapters.
- Prefer reproducible commands.
- Avoid unnecessary complexity.