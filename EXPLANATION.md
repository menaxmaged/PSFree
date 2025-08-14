# PSFree Project Overview

This document explains the purpose and contents of each file and folder in the PSFree repository.

## Top-Level Files

- **about.html**: Information or documentation about the project.
- **index.html**: Main entry point for the web interface.
- **cache.html**: Likely related to cache management or display.
- **alert.mjs**: JavaScript module for handling alerts or notifications.
- **config.mjs**: Configuration settings for the project.
- **lapse.mjs**: Handles lapse-related logic, possibly timing or session management.
- **psfree.mjs**: Main JavaScript module, likely the core logic of the project.
- **send.mjs**: Module for sending data or payloads.
- **payload.bin**: Binary file, possibly a payload for exploitation.
- **psfree_lapse.cache**: Cache file, stores runtime or session data.
- **COPYING**: Contains copyright information.
- **LICENSE**: Project license details.
- **README.md**: Project overview, usage instructions, and documentation.

## Fonts Folder

- **fonts/**: Contains font files and related licenses for UI or code display.
  - **FONTS.LICENSE**: License for the included fonts.
  - **LiberationMono-Regular.ttf**: Font file.
  - **README.txt**: Information about the fonts.

## kpatch Folder

- **kpatch/**: Contains files for low-level patching or exploits, likely for PlayStation systems.
  - **900.c, 900.d, 900.elf, 900.o**: C source, data, ELF binary, and object files for exploits or patches.
  - **Makefile**: Build instructions for the C code.
  - **script.ld**: Linker script for building binaries.
  - **types.h, utils.h**: Header files for type definitions and utilities.

## module Folder

- **module/**: JavaScript modules for various utilities and memory operations.
  - **chain.mjs**: Handles chain logic, possibly for exploit chains.
  - **constants.mjs**: Defines constants used throughout the project.
  - **int64.mjs**: Utilities for 64-bit integer operations.
  - **mem.mjs, memtools.mjs**: Memory manipulation and tools.
  - **offset.mjs**: Manages offsets for memory or data structures.
  - **rw.mjs**: Read/write operations.
  - **utils.mjs**: General utility functions.
  - **view.mjs**: Handles view or UI logic.

## rop Folder

- **rop/**: Contains modules for Return-Oriented Programming (ROP) chains or exploit logic.
  - **900.mjs**: ROP chain logic for a specific exploit or system version.

---

This project appears to be a toolkit or exploit framework, likely targeting PlayStation systems, with both web-based and low-level binary components. If you need a deeper explanation of any specific file or folder, please ask!
