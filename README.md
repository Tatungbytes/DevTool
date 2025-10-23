TatungBytes Toolkit v2.0.1

TatungBytes Toolkit is an all-in-one GUI tool for building and testing Tatung Einstein Z80 assembly projects.
It automates the process of assembling .asm source files into .COM executables, packaging them into CP/M-compatible .DSK images, and launching them directly in MAME with one click.

Now supports "Boot Direct" mode — injects a bootloader and bypasses DOS80 completely.

Features

Z80 Assembly Automation — Build .asm → .COM → .DSK with a single click.

CP/M Disk Creation — Uses z88dk-appmake to generate disk images.

One-click Run in MAME — Automatically starts MAME with your generated disk image.

Boot Direct Mode — Skips DOS80 and injects a direct bootloader into your disk image.

GUI Interface — Built with tkinter (and optional ttkbootstrap for a modern look).

Logging — All build output is saved to timestamped log files under ~/Documents/Logs.

Auto Path Management — Handles missing runtime directories and normalizes file names automatically.

Requirements
System

Linux desktop environment (X11 or Wayland)

Python 3.8+

MAME (configured for Tatung Einstein emulation)

z88dk toolchain (for z80asm and z88dk-appmake)
