---
title: "Versions"
summary: "General summary of versions."
draft: false
toc: true
sidebar_position: 1
---

This page details general information about PCSX2 versions as well as the specific versions that dropped support for various operating systems, plugins, APIs, architectures, etc.

## Stable and nightly versions

PCSX2 periodically releases stable versions. These are for users who don't want to deal with changing dependencies, changing savestate versions, potential regressions, and frequent updates.

PCSX2 also releases nightly versions in a rolling release model. These come out shortly after a new commit is merged into PCSX2 – usually at least once per day. Users on the bleeding edge generally have more emulation accuracy and speed, more bug fixes, and a more polished UI. 

Each PCSX2 version has three digits separated by decimal points in descending order of significance from left to right. The parity (evenness or oddness) of the middle digit indicates whether it is a stable or a nightly version. Stable versions after v1.0.0 have an even middle digit, while nightly versions (previously "developer" or "unstable" versions) have an odd middle digit. As soon as a stable version is released, the corresponding nightly versions begin releasing and eventually bridge the gap between the current and next stable version. For example, v2.2.0 is stable, v2.4.0 is stable, and v2.3.X are nightlies developed inbetween those.

## Major deprecations

:::caution
The PCSX2 Team does not support outdated versions of PCSX2. You will need to update to the latest nightly version before receiving support. Bug reports for the latest stable are considered only for critical problems which require the prompt release of another stable version. Reports of problems prior to the latest stable are not supported whatsoever.
:::

PCSX2 will drop support for various third-party software (and occasionally hardware) when we determine that retaining support is detrimental to an overwhelming majority of users or that it has substantially deteriorated with no way for us to practicably support it. Nonetheless, we retain legacy versions on our site for users of legacy software and hardware.

Below is a list of stable and nightly versions just prior to major deprecations. The nightly versions represent the last commit before support was formally dropped, which is often done because something is broken; thus, they may not function correctly and it is highly recommended you choose the stable version without a *very specific reason* to choose the nightly. For the current minimum hardware and software requirements, please see [the Requirements page](https://pcsx2.net/docs/setup/requirements).

### Windows support

This section has the last versions of PCSX2 to support various versions of Windows.

#### Windows 8/8.1

- Stable: v1.6.0
- Nightly: v1.7.3581

#### Windows 7

- Stable: v1.6.0
- Nightly: v1.

#### Windows Vista

- Stable: v1.4.0
- Nightly: [v1.6.0-rc](https://github.com/PCSX2/pcsx2/releases/tag/v1.6.0-rc)

#### Windows XP

- Stable: v1.4.0
- Nightly: [v1.5.0-dev-460](https://forums.pcsx2.net/Thread-Windows-XP-support-v2)

### macOS

This section has the last versions of PCSX2 to support various versions of macOS. Support for macOS began on PCSX2 version targeting a minimum of macOS 10.14 ("Mojave").

#### Mojave (10.14)

- Stable: N/A
- Nightly: [v1.7.5107](https://github.com/PCSX2/pcsx2/releases/tag/v1.7.5107)

#### Catalina (10.15)

- Stable: N/A
- Nightly: [v1.7.5107](https://github.com/PCSX2/pcsx2/releases/tag/v1.7.5107)

### Linux

Support for Linux was introduced in PCSX2 v0.0.38. It was temporarily dropped in v1.4.0 but returned in v1.6.0. Because of the enormous variety of release models, desktop environments, and distributions, PCSX2 does not explicitly target specific versions of Linux desktops – with the lone exception of Ubuntu. Although PCSX2 should run on all major desktop environments (e.g. KDE, GNOME, MATE, Cinnamon, Sway, Budgie, Xfce), both major display servers (Wayland and Xorg), and all of the latest versions of major distributions (e.g. Debian, Arch, SUSE, RHEL, NixOS, Gentoo), only a small combination of these are tested by PCSX2's contributors.

#### Ubuntu 22.04

- Stable: v2.4.0
- Nightly: https://github.com/PCSX2/pcsx2/pull/12946

#### Ubuntu 20.04

- Stable: v1.6.0
- Nightly: [v1.7.4714](https://github.com/PCSX2/pcsx2/releases/tag/v1.7.4714)

### Architectures

#### 32-bit

- Stable: v1.6.0
- Nightly: [v1.7.2484](https://github.com/PCSX2/pcsx2/releases/tag/v1.7.2484)

#### SSE2

- Stable: v1.6.0
- Nightly: v1.7.?

#### SSE3

- Stable: v1.6.0
- Nightly: v1.7.?

### Graphics APIs

#### DirectX 10

- Stable: v1.6.0
- Nightly: [v1.7.4832](https://github.com/PCSX2/pcsx2/releases/tag/v1.7.4832)

### Miscellaneous

#### Plugins

PCSX2 used to operate on a plugin system for components like graphics, audio, storage, networking, and user input. These plugins were merged, and standalone plugins can no longer interface with PCSX2.

- Stable: v1.6.0
- Nightly: v1.7.0-dev-1419

#### wxWidgets

Before Qt, PCSX2 used wxWidgets for its GUI.

- Stable: v1.6.0
- Nightly: [v1.7.3771](https://github.com/PCSX2/pcsx2/releases/tag/v1.7.3771)


<!--<Image src={require("./img/ffmpeg.webp").default} />-->
