# Pawn Language Service

A maintained and modernized fork of the original **AMXXPawn Language** VS Code extension, originally authored by **KliPPy**.

This fork is maintained by **Bogdan Deaconu** and focuses on keeping the extension working on modern VS Code versions while preserving the original behavior and features, now under the name **Pawn Language**.

---

## Features

- Syntax highlighting for Pawn (`.sma`, `.inc`, `.sp`, `.pwn`) with extension-aware variants
- Autocomplete for functions, variables, and constants
- Hover documentation and signature help (including doc-comments)
- Go to Definition / Peek Definition for functions and global variables
- Diagnostics from `amxxpc` warnings and errors
- `#include` / `#tryinclude` parsing, linking, and diagnostics
- Optional Web API links for default AMXX includes

## Notes

- All Pawn file types use the `Pawn` language mode by default; the server tracks variants by extension (`.sma` = AMXX, `.sp` = SourcePawn, `.pwn` = SA-MP).

---

## Requirements

To compile plugins from VS Code you need an AMXX compiler (`amxxpc`).

You can use the compiler from the official AMX Mod X package, or your own setup.
