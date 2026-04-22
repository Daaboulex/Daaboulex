<p align="center">
  <a href="https://github.com/Daaboulex">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=3000&pause=1000&color=B060C0&center=true&vCenter=true&repeat=false&width=600&height=45&lines=Stephan+Daaboul" alt="Stephan Daaboul"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/Daaboulex">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=3000&pause=2000&color=82D44A&center=true&vCenter=true&width=700&height=25&lines=Embedded+Systems+Engineer;NixOS+Package+Maintainer;Arm+Cortex-M+%7C+Kernel+Patching+%7C+Nix+Flakes" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/Daaboulex?tab=repositories"><img src="https://img.shields.io/badge/NixOS-unstable-78C0E8?style=for-the-badge&logo=nixos&logoColor=white" alt="NixOS"></a>
  <a href="https://github.com/Daaboulex?tab=repositories"><img src="https://img.shields.io/badge/Kernel-CachyOS--LTO-F08030?style=for-the-badge&logo=linux&logoColor=white" alt="Kernel"></a>
  <a href="https://www.linkedin.com/in/stephan-daaboul/"><img src="https://img.shields.io/badge/LinkedIn-Connect-B060C0?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/Daaboulex"><img src="https://img.shields.io/github/followers/Daaboulex?label=Follow&style=for-the-badge&logo=github&color=82D44A" alt="Followers"></a>
  <img src="https://komarev.com/ghpvc/?username=Daaboulex&style=for-the-badge&color=F08030&label=Profile+Views" alt="Profile Views">
</p>

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-About_Me-B060C0?style=for-the-badge&labelColor=1a1b27" alt="About Me"/>

Embedded Systems Engineer at **Fahlke Control Systems KG** (Germany). Day job is Arm Cortex-M4 firmware for industrial valve controllers — FreeRTOS, Modbus RTU/TCP, HART, dual-bank updates, IEC 61508 / 61511 safety constraints. The surrounding ecosystem is ESP32 gateways, MQTT, a React Native field-service app, and a .NET/Avalonia configuration tool. I wrote most of our build system: a PowerShell toolchain that generates Makefiles from a manifest, wraps the flash pipeline for three MCU families, and hooks into VSCode tasks so the same commands work on Windows at the bench and on Linux in CI.

B.Sc. Robotics and Intelligent Systems, Jacobs University Bremen. Arm Cortex-M architecture + embedded software design certifications. Native Spanish and English; learning German.

Not a computer scientist — an engineer who stitches things together until they work and then keeps them working. Outside of work I maintain 22 Nix repos for software that either isn't in nixpkgs, lags upstream, or is my own. I also run a two-host NixOS config (desktop + MacBook) that's become the main playground for everything I'm opinionated about: reproducibility, host-specific tuning, and build discipline.

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Packages_I_Maintain-78C0E8?style=for-the-badge&labelColor=1a1b27" alt="NixOS Packages"/>

22 repos. Most are packaging wrappers around upstream projects that nixpkgs doesn't ship or ships late; five are my own code. All share a [packaging standard](https://github.com/Daaboulex/nixos-ai-context/blob/main/repo-standard/REPO-STANDARD.md) (v1.2) — same `flake.nix` shape, same CI template, same `sync.sh` that keeps the fleet aligned. Daily cron updates, per-repo ELF/binary smoke tests, no-AI-file CI gate, branch protection, SECURITY.md.

**Authored by me** (not wrapping an upstream binary)

<table>
  <tr>
    <td align="center" width="160"><a href="https://github.com/Daaboulex/linux-corecycler"><b>linux-corecycler</b></a></td>
    <td>CoreCycler ported from Windows to Linux. Per-core AMD Ryzen stability tester driven by PBO Curve Optimizer offsets. PySide6 sidebar, smart-backoff scheduling, CO-profile save/restore. The Linux port didn't exist before.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/rocksmith-nix"><b>rocksmith-nix</b></a></td>
    <td>Makes Rocksmith 2014 actually playable on Linux. Bundles WineASIO, rs-asio, rs-autoconnect, and a patch-rocksmith tool that strips the game's DRM checks for offline use. The combination is what separates "launches" from "usable for practice."</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/goxlr-hm-nix"><b>goxlr-hm-nix</b></a></td>
    <td>Declarative Home Manager module for GoXLR. Profile, mic profile, EQ, de-esser, and routing all live in your flake instead of in GoXLR Utility's GUI. Handy when you reinstall; painful to set up once.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/vfio-stealth-nix"><b>vfio-stealth-nix</b></a></td>
    <td>VM anti-detection stack for VFIO passthrough. ACPI/SMBIOS masking, QEMU CPU topology tweaks, KVM hidden state, OVMF patches, timing fixes. Opinionated defaults that pass the common hypervisor checks without needing to become an expert on each.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/vkBasalt_overlay_wayland"><b>vkbasalt-overlay</b></a></td>
    <td>Fork of vkBasalt that adds an in-game ImGui overlay for live shader tuning. Works on Wayland, not just X11.</td>
  </tr>
</table>

**Packaging upstream software for NixOS** — maintained because nixpkgs either doesn't ship it, ships it stale, or I want build-from-source with my own knobs.

<table>
  <tr>
    <td align="center" width="160"><a href="https://github.com/Daaboulex/mesa-git-nix"><b>mesa-git-nix</b></a></td>
    <td>Mesa from <code>main</code> — every 12h. Useful when a Vulkan/VAAPI bug fix lands days before the stable release.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/cachyos-settings-nix"><b>cachyos-settings-nix</b></a></td>
    <td>CachyOS's upstream system tuning (sysctls, udev, I/O schedulers, ZRAM, THP, audio) as a standalone NixOS module. No kernel dependency — use the tuning with any kernel.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/portmaster-nix"><b>portmaster-nix</b></a></td>
    <td>Safing Portmaster — per-app egress firewall. NixOS module wires settings into <code>/etc/portmaster/config.json</code> with a <code>forceSettings</code> tier that reasserts keys UI edits can otherwise revert. Pairs with a small watcher that keeps Mullvad's fwmark alive when Portmaster touches CONNMARK.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/mullvad-vpn-nix"><b>mullvad-vpn-nix</b></a></td>
    <td>Mullvad VPN tracked against upstream (GitHub releases). Declarative daemon settings via the <code>mullvad</code> CLI, HM module for GUI prefs, version pin so Mullvad updates when I choose, not on every <code>nix flake update</code>.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/coolercontrol-nix"><b>coolercontrol-nix</b></a></td>
    <td>CoolerControl daemon + GUI + CLI, with an HM layer for autostart and tray integration. Includes an API schema monitor so upstream breaking changes surface in CI instead of at runtime.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/OCCT-nix"><b>OCCT-nix</b></a></td>
    <td>OCCT stress/bench/monitor. Proprietary upstream, wrapped into a usable <code>nix run</code> entry point.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/yeetmouse-nix"><b>yeetmouse-nix</b></a></td>
    <td>Kernel module for non-Windows mouse acceleration curves. Ships upstream's eight accel modes with the kernel build + udev rules sorted out for NixOS.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/streamcontroller-nix"><b>streamcontroller-nix</b></a></td>
    <td>StreamController (Elgato Stream Deck, open-source). Packaging + udev rules + HM module for declarative page/deck layouts.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/lsfg-vk-nix"><b>lsfg-vk-nix</b></a></td>
    <td>Lossless Scaling Frame Generation as a Vulkan layer for Linux-native + Proton games. Tracks the <code>v2.0.0-dev</code> branch.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/eden-nix"><b>eden-nix</b></a></td>
    <td>Eden — active Yuzu fork after Nintendo's takedown. Gitea commit tracking (upstream isn't on GitHub), wrapped with the Qt/Vulkan runtime dependencies a Switch emulator actually needs.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/nx-save-sync-nix"><b>nx-save-sync-nix</b></a></td>
    <td>nx_save_sync for Nintendo Switch save files. Desktop entry wired so it launches from the app menu instead of needing a terminal.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/lmstudio-nix"><b>lmstudio-nix</b></a></td>
    <td>LM Studio desktop app and CLI server. Proprietary upstream; tracked via a custom updater because LM Studio doesn't use GitHub releases.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/gemini-cli-nix"><b>gemini-cli-nix</b></a></td>
    <td>Google's gemini-cli. Three channels (stable, preview, nightly) pinned to npm dist-tags so I can compare-and-contrast on the same machine.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/models-nix"><b>models-nix</b></a></td>
    <td>arimxyer/models — a TUI for browsing and running local/remote LLMs side-by-side.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/openviking-nix"><b>openviking-nix</b></a></td>
    <td>OpenViking — context store for AI agents. Packaged for the stack I run alongside Claude Code and Gemini.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/ripgrep-nix"><b>ripgrep-nix</b></a></td>
    <td>ripgrep tracking upstream releases. Exists because nixpkgs sometimes sits on an older tag and I want the latest features (multiline improvements, new flags) the week they ship.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/Daaboulex/durdraw-nix"><b>durdraw-nix</b></a></td>
    <td>durdraw — terminal ANSI/ASCII/Unicode art editor. Handy for writing the banners in my own CLIs.</td>
  </tr>
</table>

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-System_Configuration-F08030?style=for-the-badge&labelColor=1a1b27" alt="System Configuration"/>

<a href="https://github.com/Daaboulex/nixos"><b>nixos</b></a> — modular flake-parts config. Two hosts; everything host-specific lives in one place per host, everything shared is a module with a `myModules.*` option.

> **Dendritic** — features branch into their own small module with an explicit option interface. Every module exports via `flake.modules.nixos.<scope>-<name>` or the Home Manager equivalent. A path-aware pre-commit hook rejects modules declared in the wrong directory.
>
> **Host-aware tuning** — desktop (Ryzen 9950X3D + RX 9070 XT, CachyOS LTO kernel) and MacBook Pro 9,2 (Ivy Bridge, 2C/4T, dual kernel: xanmod default + cachyos-lto-v2 specialisation). I/O scheduler, earlyoom thresholds, sysctls, and fan curves are chosen per host from measured evidence, not copy-pasted tips.
>
> **Scheduler** — currently EEVDF on both hosts. scx_lavd was the previous default and will come back on kernel 7.1 once Tejun's cgroup_move fix lands; pinned tracker in the roadmap. Governor ladder with a small module that picks `performance` on AC and `schedutil` on battery.
>
> **AI-augmented workflow** — Claude Code, Gemini CLI, Kiro, OpenCode, LM Studio, and a small MCP server for context. Hooks auto-commit session memory + skills to a private repo and sync Claude ↔ Gemini config bidirectionally.
>
> **Automation** — `nrb` build wrapper (with a new `--update-no-kernel` flag that autonomously skips kernel-rebuilding input bumps via speculative eval), disko for partitioning, nine enforcing pre-commit hooks (placement, docstrings, `mkForce`-comment requirements, `with lib;` ban, eval check, README section regen), NixOS VM integration tests for security-sops and impermanence paths.
>
> **Numbers** — ~220 `myModules.*` option paths, 75 NixOS modules, 148 Home Manager modules, 25 overlays, 22 external repos locked in as inputs.

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Tech-82D44A?style=for-the-badge&labelColor=1a1b27" alt="Tech"/>

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,linux,bash,powershell,nix,dotnet,arduino,vscode,github,python&theme=dark" alt="Tech Stack"/>
</p>

<table align="center">
  <tr>
    <td><b>Embedded</b></td>
    <td><code>Arm Cortex-M4 (LPC4337)</code> <code>C</code> <code>C++</code> <code>FreeRTOS</code> <code>ESP32</code> <code>Modbus RTU/TCP</code> <code>HART</code> <code>COBS</code> <code>USB CDC</code> <code>IEC 61508/61511</code></td>
  </tr>
  <tr>
    <td><b>Desktop / Mobile</b></td>
    <td><code>.NET</code> <code>Avalonia</code> <code>React Native (Expo)</code> <code>MQTT</code></td>
  </tr>
  <tr>
    <td><b>Build tooling</b></td>
    <td><code>PowerShell</code> <code>Makefile codegen</code> <code>VSCode tasks</code> <code>Windows + Linux dev parity</code></td>
  </tr>
  <tr>
    <td><b>NixOS</b></td>
    <td><code>Flakes</code> <code>flake-parts</code> <code>Home Manager</code> <code>treefmt</code> <code>disko</code> <code>sops-nix</code> <code>impermanence</code> <code>Secure Boot (lanzaboote)</code></td>
  </tr>
  <tr>
    <td><b>Linux internals</b></td>
    <td><code>Vulkan</code> <code>Mesa</code> <code>AMDGPU</code> <code>kernel patches</code> <code>btrfs</code> <code>LUKS</code> <code>VFIO</code> <code>zram</code> <code>systemd-resolved DoT</code></td>
  </tr>
  <tr>
    <td><b>Audio / creative</b></td>
    <td><code>PipeWire</code> <code>GoXLR</code> <code>Rocksmith</code> <code>TidalCycles</code> <code>SuperCollider</code></td>
  </tr>
  <tr>
    <td><b>Gaming</b></td>
    <td><code>Steam</code> <code>Gamescope</code> <code>MangoHud</code> <code>LSFG-VK</code> <code>vkBasalt</code> <code>Wine</code> <code>VFIO passthrough</code></td>
  </tr>
  <tr>
    <td><b>AI tooling</b></td>
    <td><code>Claude Code</code> <code>Gemini CLI</code> <code>Kiro</code> <code>OpenCode</code> <code>LM Studio</code> <code>Models CLI</code> <code>OpenViking</code> <code>MCP</code></td>
  </tr>
</table>

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Research-E8D040?style=for-the-badge&labelColor=1a1b27" alt="Research"/>

**An affordable gradient mixer for chromatography with aqueous and organic solvents**
K. Garcia, C.E. Godinez, **S. Daaboul**, P. Cendoya, G. Ramos, D. Gabel
*Journal of Chromatography A*, 2023 &mdash; [DOI: 10.1016/j.chroma.2023.463930](https://doi.org/10.1016/j.chroma.2023.463930) &bull; [Code & Hardware](https://github.com/kelangarcia/Automation_of_a_Linear_Gradient_Mixer_for_Chromatography)

<p align="center"><img src="divider.svg" width="100%"></p>

<img src="https://img.shields.io/badge/-Stats-B060C0?style=for-the-badge&labelColor=1a1b27" alt="Stats"/>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Daaboulex&hide_border=true&background=00000000&ring=F08030&fire=B060C0&currStreakLabel=78C0E8&sideLabels=78C0E8&currStreakNum=82D44A&sideNums=82D44A&dates=F08030" alt="GitHub Streak" width="49%">
</p>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Daaboulex&hide_border=true&bg_color=00000000&color=78C0E8&line=B060C0&point=F08030&area=true&area_color=B060C0" width="100%" alt="Contribution Graph"/>

<p align="center"><img src="divider.svg" width="100%"></p>
