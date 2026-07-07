# Glossary

This glossary contains recurring LPIC-3 305 terms.
Keep entries short and exam-focused.

---

## CPU flags

Processor feature flags exposed by the Linux kernel, commonly inspected through `/proc/cpuinfo`.
For virtualization, `vmx` indicates Intel VT-x and `svm` indicates AMD-V.

## Domain0 (Dom0)

The privileged Xen control domain.
Dom0 manages the Xen host, provides backend drivers and runs Xen management tools.

## DomainU (DomU)

An unprivileged Xen guest domain.
DomU guests run virtual machines on the Xen hypervisor.

## Emulation

Software imitation of another system or CPU architecture.
Emulation can run software for different hardware but is usually slower than hardware-assisted virtualization.

## Guest

The operating system running inside a virtual machine.

## Hardware Virtual Machine (HVM)

A virtual machine that uses hardware-assisted virtualization, commonly associated with Xen terminology.
HVM guests can usually run unmodified operating systems.

## HVM-DomU

A Xen guest domain that uses hardware-assisted virtualization.
HVM-DomU guests can usually run unmodified operating systems.

## Host

The physical system that provides CPU, memory, storage and network resources for virtual machines.

## Hypervisor

The virtualization layer that creates and controls virtual machines.
The term is often used similarly to Virtual Machine Monitor.

## KVM

Kernel-based Virtual Machine.
The Linux kernel virtualization facility that uses CPU virtualization extensions such as Intel VT-x or AMD-V.

## libvirt

A virtualization management framework and API used to manage virtualization backends such as QEMU/KVM.

## Migration

Moving a workload between systems or virtualization environments.
For LPIC-3 305, important forms include P2V, V2V and host-to-host VM migration.

## Open vSwitch

A virtual switch used in virtualization and cloud networking.
For 351.1, awareness is enough.

## oVirt

An open-source virtualization management platform for KVM-based environments.

## Paravirtualization (PV)

A virtualization approach where the guest is aware of the hypervisor and cooperates with it through specialized interfaces.

## PV-DomU

A Xen guest domain that uses paravirtualization.
PV-DomU guests are aware that they run under Xen and use Xen-aware interfaces.

## P2V

Physical-to-virtual migration.
The process of converting a physical machine into a virtual machine.

## Proxmox VE

A virtualization management platform that manages virtual machines and containers using technologies such as QEMU/KVM and LXC.

## QEMU

A userspace emulator and virtualizer.
With KVM, QEMU provides the VM process and virtual hardware while KVM accelerates CPU execution.

## Simulation

Modeling the behavior of a system.
Unlike emulation, simulation does not necessarily run a real guest operating system.

## Snapshot

A point-in-time capture of virtual machine state.
Snapshots are useful for rollback but are not a replacement for backups.

## systemd-machined

A systemd service that tracks local virtual machines and containers.

## Virtual Machine (VM)

A software-defined computer that runs a guest operating system using virtual hardware.

## Virtual Machine Monitor (VMM)

Software that monitors and controls virtual machines.
In many LPIC-3 contexts, the term overlaps with hypervisor.

## VirtualBox

A Type 2 desktop virtualization product commonly used for development, testing and education.

## V2V

Virtual-to-virtual migration.
The process of moving a virtual machine between virtualization platforms or formats.

## Xen

A Type 1 hypervisor.
Xen starts before Dom0 and runs privileged and unprivileged domains.

## Xen boot parameters

Options passed to the Xen hypervisor at boot time.
They are separate from Dom0 or guest Linux kernel parameters.

## XenStore

A Xen-specific key-value store used for runtime configuration, state information and communication between Xen components.

## XAPI

A Xen management API and higher-level toolstack associated with XenServer-style environments.

## `xl`

The main Xen 4.x command-line management tool.
It manages domains through the libxl toolstack.

## `xl.cfg`

The Xen domain configuration format used by `xl`.
It defines guest settings such as memory, vCPUs, disks and network interfaces.

## `xl.conf`

The global configuration file for the `xl` toolstack, usually located at `/etc/xen/xl.conf`.

## `xm`

The legacy Xen management command from the older xend toolstack.
For Xen 4.x, recognize it as older than `xl`.

## `xentop`

An interactive Xen monitoring tool that shows domain resource usage.
