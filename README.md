<h1 align="center">Stephan Daaboul</h1>

<p align="center">
  <strong>Embedded Systems Engineer | NixOS Package Maintainer</strong>
</p>

<p align="center">
  <a href="https://github.com/Daaboulex?tab=repositories"><img src="https://img.shields.io/badge/NixOS-unstable-5277C3?style=flat-square&logo=nixos&logoColor=white" alt="NixOS"></a>
  <a href="https://github.com/Daaboulex?tab=repositories"><img src="https://img.shields.io/badge/Kernel-CachyOS--LTO-orange?style=flat-square&logo=linux&logoColor=white" alt="Kernel"></a>
  <a href="https://www.linkedin.com/in/stephan-daaboul/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/Daaboulex"><img src="https://img.shields.io/github/followers/Daaboulex?label=Follow&style=flat-square&logo=github" alt="Followers"></a>
</p>

---

### About Me

Embedded Systems Engineer at **Fahlke Control Systems KG** in Germany, working with low-level hardware and control systems. B.Sc. in Robotics and Intelligent Systems from Jacobs University Bremen. Certified in Arm Cortex-M architecture and embedded software design. Native Spanish and English speaker, currently learning German.

Outside of work, I contribute to the NixOS ecosystem — packaging bleeding-edge software that doesn't exist in nixpkgs and maintaining a performance-tuned multi-host system configuration.

### NixOS Packages & Modules

| Package | Description |
|---------|-------------|
| [**mesa-git-nix**](https://github.com/Daaboulex/mesa-git-nix) | Bleeding-edge Mesa from `main` — latest Vulkan/OpenGL drivers before release |
| [**cachyos-settings-nix**](https://github.com/Daaboulex/cachyos-settings-nix) | CachyOS performance settings as a standalone NixOS module |
| [**portmaster-nix**](https://github.com/Daaboulex/portmaster-nix) | Portmaster privacy firewall packaged for NixOS |
| [**lsfg-vk-nix**](https://github.com/Daaboulex/lsfg-vk-nix) | Vulkan frame generation (Lossless Scaling) for Linux |
| [**eden-nix**](https://github.com/Daaboulex/eden-nix) | Eden Nintendo Switch emulator Nix flake |
| [**OCCT-nix**](https://github.com/Daaboulex/OCCT-nix) | OCCT hardware stress test for NixOS |
| [**nx-save-sync-nix**](https://github.com/Daaboulex/nx-save-sync-nix) | Nintendo Switch save sync tool |

### System Configuration

[**nixos**](https://github.com/Daaboulex/nixos) — Modular NixOS flake with 200+ custom options across 30+ modules:

- **Dendritic architecture** — every feature is an independent, toggleable module behind `myModules.*`
- **Performance-first** — CachyOS kernel with Zen 5 microarch compilation, bore scheduler, ananicy-cpp
- **Multi-host** — Desktop (Ryzen 9950X3D + RX 9070 XT) and MacBook Pro 9,2 with kernel specialisations
- **Automated tooling** — `nrb` build helper, auto-generated docs, config validation scripts

### Tech

```
Embedded: Arm Cortex-M / C / RTOS / Control Systems / Hardware Design
NixOS: Nix Flakes / flake-parts / Home Manager / CachyOS / Secure Boot (Lanzaboote)
Linux: Vulkan / Mesa / AMDGPU / Kernel patching / BTRFS / LUKS / sops-nix
```

---

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Daaboulex&theme=tokyonight&hide_border=true&background=00000000" alt="GitHub Streak">
</p>
