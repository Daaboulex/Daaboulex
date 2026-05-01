<p align="center">
  <a href="https://github.com/Daaboulex">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=3000&pause=1000&color=B060C0&center=true&vCenter=true&repeat=false&width=600&height=45&lines=Stephan+Daaboul" alt="Stephan Daaboul"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/Daaboulex">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=3000&pause=2000&color=82D44A&center=true&vCenter=true&width=700&height=25&lines=Embedded+Systems+Engineer;NixOS+Package+Maintainer;Arm+Cortex-M+%7C+Industrial+Control+%7C+Nix+Flakes" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/Daaboulex?tab=repositories"><img src="https://img.shields.io/badge/NixOS-unstable-78C0E8?style=for-the-badge&logo=nixos&logoColor=white" alt="NixOS"></a>
  <a href="https://www.linkedin.com/in/stephan-daaboul/"><img src="https://img.shields.io/badge/LinkedIn-Connect-B060C0?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-About_Me-B060C0?style=for-the-badge&labelColor=1a1b27" alt="About Me"/>

Embedded Systems Engineer at **Fahlke Control Systems KG** (Germany). Day job is Arm Cortex-M4 firmware for industrial valve controllers — FreeRTOS, Modbus RTU/TCP, HART, secure firmware updates, IEC 61508/61511 safety constraints. The surrounding stack is ESP32 gateways, MQTT, a React Native field-service app, and a .NET/Avalonia configuration tool. I wrote most of our build system: a PowerShell toolchain that generates Makefiles from a manifest, wraps the flash pipeline for three MCU families, and hooks into VSCode tasks so the same commands work on Windows at the bench and on Linux in CI.

B.Sc. Robotics and Intelligent Systems, Jacobs University Bremen. Arm Cortex-M architecture + embedded software design certifications. Native Spanish and English; learning German.

Not a computer scientist — an engineer who stitches things together until they work and then keeps them working.

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-What_I_Believe-F08030?style=for-the-badge&labelColor=1a1b27" alt="What I Believe"/>

- **Atomic and dendritic** — one module, one concern. Every feature is an independent branch you can graft on or prune off with a single boolean.
- **Invest now, works forever** — pick the approach that compounds over time, even if the up-front cost is higher.
- **Tools enhance, don't change** — background improvements over new commands. If it changes how you type, it's wrong.
- **Measure before tuning** — evidence first, then optimize. No copy-pasted tips.

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Research-E8D040?style=for-the-badge&labelColor=1a1b27" alt="Research"/>

**An affordable gradient mixer for chromatography with aqueous and organic solvents**
K. Garcia, C.E. Godinez, **S. Daaboul**, P. Cendoya, G. Ramos, D. Gabel
*Journal of Chromatography A*, 2023 &mdash; [DOI: 10.1016/j.chroma.2023.463930](https://doi.org/10.1016/j.chroma.2023.463930) &bull; [Code & Hardware](https://github.com/kelangarcia/Automation_of_a_Linear_Gradient_Mixer_for_Chromatography)

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Highlights-82D44A?style=for-the-badge&labelColor=1a1b27" alt="Highlights"/>

<table>
  <tr>
    <td align="center" width="160"><a href="https://github.com/Daaboulex/linux-corecycler"><b>linux-corecycler</b></a></td>
    <td>CoreCycler ported from Windows to Linux. Per-core AMD Ryzen stability tester for PBO Curve Optimizer offsets. PySide6 GUI, smart-backoff scheduling, CO-profile save/restore. The Linux port didn't exist before I wrote it.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/vkBasalt_overlay_wayland"><b>vkBasalt overlay</b></a></td>
    <td>Fork of vkBasalt that adds an in-game ImGui overlay for live shader tuning. Works on Wayland, not just X11.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/kachow"><b>kachow</b></a></td>
    <td>Portable hook framework for AI coding agents. One rules file, every tool on your machine follows it — Claude Code, Gemini CLI, Codex, OpenCode, Aider, Cursor.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/vfio-stealth-nix"><b>vfio-stealth-nix</b></a></td>
    <td>VM anti-detection stack for VFIO passthrough. ACPI/SMBIOS masking, QEMU CPU topology tweaks, KVM hidden state, OVMF patches, timing fixes. Opinionated defaults that pass hypervisor checks without needing to become an expert on each.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/nixos"><b>nixos</b></a></td>
    <td>Modular NixOS flake for two hosts. Dendritic architecture — every concern branches into its own module with an explicit option interface. Enforcing pre-commit hooks, VM integration tests, host-specific tuning from measured evidence.</td>
  </tr>
</table>

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-All_Packages-78C0E8?style=for-the-badge&labelColor=1a1b27" alt="All Packages"/>

NixOS packages I maintain — packaging upstream software that nixpkgs doesn't ship, ships stale, or that I want built from source with my own knobs. All share a [packaging standard](https://github.com/Daaboulex/nixos/blob/main/docs/REPO-STANDARD.md).

<!-- BEGIN auto:repos -->
<!-- This table is auto-generated by .github/workflows/update-readme.yml — do not edit manually -->

| Repo | Description |
|---|---|
| [cachyos-settings-nix](https://github.com/Daaboulex/cachyos-settings-nix) | CachyOS settings packaged for NixOS — system performance tuning module |
| [coolercontrol-nix](https://github.com/Daaboulex/coolercontrol-nix) | CoolerControl packaged for NixOS — fan and cooling device monitoring and control |
| [durdraw-nix](https://github.com/Daaboulex/durdraw-nix) | Duradraw packaged for NixOS — Unicode/ANSI/ASCII art editor for the terminal |
| [eden-nix](https://github.com/Daaboulex/eden-nix) | Eden packaged for NixOS — Nintendo Switch emulator |
| [gemini-cli-nix](https://github.com/Daaboulex/gemini-cli-nix) | Gemini CLI packaged for NixOS — AI agent in your terminal |
| [goxlr-hm-nix](https://github.com/Daaboulex/goxlr-hm-nix) | GoXLR Utility Home Manager module — declarative mixer configuration via goxlr-client |
| [lmstudio-nix](https://github.com/Daaboulex/lmstudio-nix) | LM Studio packaged for NixOS — local LLM inference desktop app and server |
| [lsfg-vk-nix](https://github.com/Daaboulex/lsfg-vk-nix) | LSFG-VK packaged for NixOS — Vulkan frame generation for Linux |
| [mesa-git-nix](https://github.com/Daaboulex/mesa-git-nix) | Mesa from git main packaged for NixOS — bleeding-edge GPU drivers |
| [models-nix](https://github.com/Daaboulex/models-nix) | Models CLI packaged for NixOS — TUI for browsing AI models, benchmarks, and coding agents |
| [mullvad-vpn-nix](https://github.com/Daaboulex/mullvad-vpn-nix) | Mullvad VPN packaged for NixOS — declarative daemon settings, Home Manager GUI prefs, upstream version pin |
| [nx-save-sync-nix](https://github.com/Daaboulex/nx-save-sync-nix) | NX Save Sync packaged for NixOS — Nintendo Switch save file synchronization |
| [OCCT-nix](https://github.com/Daaboulex/OCCT-nix) | OCCT packaged for NixOS — hardware stress testing, benchmarking, and monitoring |
| [openviking-nix](https://github.com/Daaboulex/openviking-nix) | OpenViking packaged for NixOS — agent-native context database for AI agents |
| [portmaster-nix](https://github.com/Daaboulex/portmaster-nix) | Portmaster packaged for NixOS — application firewall with system tray integration |
| [refind-nix](https://github.com/Daaboulex/refind-nix) | rEFInd bootloader packaged for NixOS — declarative config, themed boot, security validation |
| [ripgrep-nix](https://github.com/Daaboulex/ripgrep-nix) | ripgrep packaged for NixOS — fast recursive grep replacement, built from source |
| [rocksmith-nix](https://github.com/Daaboulex/rocksmith-nix) | Rocksmith 2014 packaged for NixOS — WineASIO, rs-autoconnect, and patch-rocksmith |
| [streamcontroller-nix](https://github.com/Daaboulex/streamcontroller-nix) | StreamController packaged for NixOS — Elgato Stream Deck control with CLI and declarative config |
| [yeetmouse-nix](https://github.com/Daaboulex/yeetmouse-nix) | YeetMouse packaged for NixOS — kernel mouse acceleration driver with 8 accel modes |

<!-- END auto:repos -->

<p align="center"><img src="divider.svg" width="100%"></p>
