# Nyveil Optimization Tweaks for Windows 11

Nyveil Win11 Optimizer is a standalone Windows optimization utility inspired by community performance tweak scripts.

Some concepts are based on publicly available optimization ideas, including:
https://github.com/lyto11/Performance-Tweaks-For-Win11

This tool provides a simple GUI that allows users to selectively apply system tweaks related to CPU scheduling, GPU behavior, memory management, services, and Windows gaming features.

---

## Features

The tool allows enabling/disabling the following optimization modules:

- Power Plan optimization (High Performance mode)
- CPU scheduling adjustments for reduced latency
- GPU optimizations (Hardware-Accelerated GPU Scheduling)
- Game DVR / Xbox services disabling
- Windows Game Mode configuration
- Memory management tweaks
- Background service reduction
- Visual performance mode (disables UI animations)

---

## Interface

The application is built with a simple Tkinter-based GUI:

- Checkbox-based tweak selection
- One-click apply system changes
- Admin elevation support
- Verification system to confirm applied changes

---

## How it works

Nyveil Optimization Tweaks modifies system-level settings including:

- Windows Registry keys
- Power configuration (powercfg)
- Windows services (sc config / stop)
- System performance flags

Some changes require a system restart to fully apply.

---

## Important Notes

This tool is designed for gaming-focused systems.

- Some tweaks may reduce system background features
- Changes can affect system behavior outside of gaming
- Use on personal systems only

It is recommended to create a restore point before applying changes.

---

## Technical Info

- Language: Python
- GUI: Tkinter
- System interaction: subprocess + Windows registry edits
- Requires administrator privileges

---

## Planned Features

- Performance benchmarking tool
- Safe rollback system
- GitHub auto-update integration

---

## Disclaimer

This software modifies Windows system settings.

The author is not responsible for:
- system instability
- performance degradation
- software incompatibility
- user misconfiguration

Use at your own risk.
