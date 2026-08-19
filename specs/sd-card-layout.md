# SD Card Layout

This document defines the filesystem contract shared by the desktop software and player firmware.

The exact layout is not yet finalized.

## Goals

- Support large music collections.
- Keep the layout understandable without proprietary tools.
- Allow the desktop software to update metadata without rewriting the entire card.
- Keep parsing practical for an ESP32-class device.

## Initial Concept

```text
/
├── Music/
└── .player/
