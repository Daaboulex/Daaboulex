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

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-About_Me-B060C0?style=for-the-badge&labelColor=1a1b27" alt="About Me"/>

Embedded Systems Engineer at **Fahlke Control Systems KG** (Germany). Day job is Arm Cortex-M4 firmware for industrial valve controllers — FreeRTOS, Modbus RTU/TCP, HART, secure firmware updates, IEC 61508/61511 safety constraints. The surrounding stack is ESP32 gateways, MQTT, a React Native field-service app, and a .NET/Avalonia configuration tool. I wrote most of our build system: a PowerShell toolchain that generates Makefiles from a manifest, wraps the flash pipeline for three MCU families, and hooks into VSCode tasks so the same commands work on Windows at the bench and on Linux in CI.

B.Sc. Robotics and Intelligent Systems, Jacobs University Bremen. Arm Cortex-M architecture + embedded software design certifications. Native Spanish and English; learning German.

Not a computer scientist — an engineer who stitches things together until they work and then keeps them working.

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Principles-F08030?style=for-the-badge&labelColor=1a1b27" alt="Principles"/>

- **Atomic and dendritic** — one module, one concern. Every feature is an independent branch you can graft on or prune off with a single boolean.
- **Invest now, works forever** — pick the approach that compounds over time, even if the up-front cost is higher.
- **Tools enhance, don't change** — background improvements over new commands. The best tool is one you don't notice.
- **Measure before tuning** — evidence first, then optimize. No copy-pasted tips.

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Research-E8D040?style=for-the-badge&labelColor=1a1b27" alt="Research"/>

**An affordable gradient mixer for chromatography with aqueous and organic solvents**
K. Garcia, C.E. Godinez, **S. Daaboul**, P. Cendoya, G. Ramos, D. Gabel
*Journal of Chromatography A*, 2023 &mdash; [DOI: 10.1016/j.chroma.2023.463930](https://doi.org/10.1016/j.chroma.2023.463930) &bull; [Code & Hardware](https://github.com/kelangarcia/Automation_of_a_Linear_Gradient_Mixer_for_Chromatography)

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Projects_I_Built-82D44A?style=for-the-badge&labelColor=1a1b27" alt="Projects I Built"/>

<table>
  <tr>
    <td align="center" width="160"><a href="https://github.com/Daaboulex/linux-corecycler"><b>linux-corecycler</b></a></td>
    <td>CoreCycler ported from Windows to Linux. Per-core AMD Ryzen stability tester for PBO Curve Optimizer offsets. PySide6 GUI, smart-backoff scheduling, CO-profile save/restore. The Linux port didn't exist before I wrote it.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/kachow"><b>kachow</b></a></td>
    <td>Portable hook framework for AI coding agents. One rules file, every tool on your machine follows it — Claude Code, Gemini CLI, Codex, OpenCode, Aider, Cursor.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/vkBasalt_overlay_wayland"><b>vkBasalt overlay</b></a></td>
    <td>Fork of vkBasalt — added an in-game ImGui overlay for live shader tuning and Wayland support. Upstream was X11-only.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/rocksmith-nix"><b>rocksmith-nix</b></a></td>
    <td>Fork — bundled WineASIO, rs-asio, rs-autoconnect, and a DRM patch tool into one package that makes Rocksmith 2014 actually playable on Linux instead of just launchable.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/nixos"><b>nixos</b></a></td>
    <td>My NixOS config. Two hosts, dendritic architecture — every concern gets its own module with an explicit option interface. Enforcing pre-commit hooks, VM integration tests, host-specific tuning from measured evidence.</td>
  </tr>
</table>

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-NixOS_Packages-78C0E8?style=for-the-badge&labelColor=1a1b27" alt="NixOS Packages"/>

Packaging upstream software for NixOS — things nixpkgs doesn't ship, ships stale, or that I want built from source. I didn't write these tools; I wrote the Nix packaging, modules, and CI around them. All share a [packaging standard](https://github.com/Daaboulex/nixos/blob/main/docs/REPO-STANDARD.md). Issues and PRs welcome.

**With custom NixOS/HM modules** — declarative config, API integration, settings tiers, or substantial module logic beyond basic packaging:

<table>
  <tr>
    <td align="center" width="160"><a href="https://github.com/Daaboulex/vfio-stealth-nix"><b>vfio-stealth-nix</b></a></td>
    <td>NixOS module integrating several upstream anti-detection projects (QEMU patches, OVMF, ACPI SSDTs) into one declarative config for GPU-passthrough gaming setups. Techniques credit upstream; the Nix integration and ACPI generation are mine.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/goxlr-hm-nix"><b>goxlr-hm-nix</b></a></td>
    <td>Home Manager module for GoXLR. Profile, mic profile, EQ, de-esser, and routing declared in your flake instead of GoXLR Utility's GUI.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/portmaster-nix"><b>portmaster-nix</b></a></td>
    <td>Portmaster built from source (Go + Rust/Tauri + Angular). NixOS module with <code>forceSettings</code> tier that reasserts keys the UI would otherwise revert.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/cachyos-settings-nix"><b>cachyos-settings-nix</b></a></td>
    <td>CachyOS system tuning re-expressed as NixOS module options. Not a copy of the Arch files — a translation into Nix module shape. No kernel dependency.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/mullvad-vpn-nix"><b>mullvad-vpn-nix</b></a></td>
    <td>NixOS module + HM module + version pinning. Declarative daemon settings via jq-patch, schema-gated.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/coolercontrol-nix"><b>coolercontrol-nix</b></a></td>
    <td>CoolerControl daemon + GUI + CLI with HM module for REST API integration (profiles, modes, alerts applied on login).</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/streamcontroller-nix"><b>streamcontroller-nix</b></a></td>
    <td>StreamController with NixOS module (udev) + HM module (declarative page/button config, device serial mapping) + CLI.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/mesa-git-nix"><b>mesa-git-nix</b></a></td>
    <td>Mesa from <code>main</code> via overlay. NixOS module for one-line GPU driver swap with vendor-aware presets.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/refind-nix"><b>refind-nix</b></a></td>
    <td>Declarative rEFInd module with typed options, theme generation, and security validation (PE binary detection, directive whitelist).</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/gemini-cli-nix"><b>gemini-cli-nix</b></a></td>
    <td>Three channels (stable, preview, nightly) tracked independently via npm dist-tags. Overlay exposes all three.</td>
  </tr>
</table>

**Standard packaging** — upstream software wrapped for `nix run` / `nix profile install` with CI and automatic updates:

<!-- BEGIN auto:repos -->
<!-- This table is auto-generated by .github/workflows/update-readme.yml — do not edit manually -->

| Repo | Description |
|---|---|
| [durdraw-nix](https://github.com/Daaboulex/durdraw-nix) | Duradraw packaged for NixOS — Unicode/ANSI/ASCII art editor for the terminal |
| [eden-nix](https://github.com/Daaboulex/eden-nix) | Eden packaged for NixOS — Nintendo Switch emulator |
| [lmstudio-nix](https://github.com/Daaboulex/lmstudio-nix) | LM Studio packaged for NixOS — local LLM inference desktop app and server |
| [lsfg-vk-nix](https://github.com/Daaboulex/lsfg-vk-nix) | LSFG-VK packaged for NixOS — Vulkan frame generation for Linux |
| [models-nix](https://github.com/Daaboulex/models-nix) | Models CLI packaged for NixOS — TUI for browsing AI models, benchmarks, and coding agents |
| [nx-save-sync-nix](https://github.com/Daaboulex/nx-save-sync-nix) | NX Save Sync packaged for NixOS — Nintendo Switch save file synchronization |
| [OCCT-nix](https://github.com/Daaboulex/OCCT-nix) | OCCT packaged for NixOS — hardware stress testing, benchmarking, and monitoring |
| [openviking-nix](https://github.com/Daaboulex/openviking-nix) | OpenViking packaged for NixOS — agent-native context database for AI agents |
| [ripgrep-nix](https://github.com/Daaboulex/ripgrep-nix) | ripgrep packaged for NixOS — fast recursive grep replacement, built from source |
| [yeetmouse-nix](https://github.com/Daaboulex/yeetmouse-nix) | YeetMouse packaged for NixOS — kernel mouse acceleration driver, patched for LTO kernel compatibility |

<!-- END auto:repos -->

<p align="center"><img src="divider.svg" width="100%"></p>

<p align="center">
  <a href="https://github.com/Daaboulex?tab=repositories"><img src="https://img.shields.io/badge/NixOS-unstable-78C0E8?style=for-the-badge&logo=nixos&logoColor=white" alt="NixOS"></a>
  <a href="https://github.com/Daaboulex?tab=repositories"><img src="https://img.shields.io/badge/Kernel-CachyOS--LTO-F08030?style=for-the-badge&logo=linux&logoColor=white" alt="Kernel"></a>
  <a href="https://www.linkedin.com/in/stephan-daaboul/"><img src="https://img.shields.io/badge/LinkedIn-Connect-B060C0?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>
