# MOS QEMU

MOS QEMU provides **packaged virtualization components** for use within the MOS ecosystem.

This repository contains the **build scripts, packaging logic, and configuration files**
required to integrate QEMU and related virtualization components into MOS.

---

## Overview

This repository packages multiple virtualization components for MOS, including
QEMU, libvirt, firmware, and TPM-related tools.

Depending on the component, binaries are either:
- built from upstream source code, or
- obtained from upstream prebuilt packages or repositories.

No functional changes to the components themselves are intended.  
The goal is to provide **consistent and reproducible virtualization packages**
for MOS installations.

---

## Included Components

The following components are packaged by this repository:

- QEMU
- libvirt
- SeaBIOS
- OVMF
- libtpms
- swtpm

A detailed overview and upstream references can be found in `THIRD_PARTY.md`.

---

## Licensing

The contents of this repository (build scripts, packaging logic, configuration, and automation)
are licensed under **GPL-3.0**.

Each packaged component remains licensed under its respective upstream license.

---

## Third-Party Software

This repository builds and packages third-party open-source software.
Packaged components remain licensed under their original upstream licenses.

Refer to `THIRD_PARTY.md` for details.
