
# Telemetry Blob

<img width="1457" height="1079" alt="telemetry-blob-public-screenshot" src="https://github.com/user-attachments/assets/21de9d8b-8e3c-418b-8aad-bfa0ad000a3e" />

A native macOS network-activity visualizer built with Swift, SwiftUI, and Metal. Local traffic, CPU activity, and optional nearby wireless observations drive an animated polygonal blob.

## Features

- Reactive movement and colors reflecting inbound and outbound activity.
- Floating endpoint addresses with optional reverse-DNS names.
- Bluetooth advertisement and nearby Wi-Fi observations.
- Adjustable traffic polling from 1–10 seconds.
- Full-window and draggable Mini modes.
- Searchable observation details, privacy controls, and reduced-motion settings.

This is a visualization tool only.

## Requirements

**Apple-silicon Mac running macOS Golden Gate 27.0.1 or later.** Xcode is not required.

## Installation

1. Download the `.dmg` file.
2. Open it and drag **Telemetry Blob** into **Applications**.
3. Eject the disk image and launch the app.
4. Enable Bluetooth or Nearby Wi-Fi if desired, then grant the corresponding macOS permissions.

**Signing notice:** This early test build is ad-hoc signed and **not notarized by Apple**. macOS may block it, particularly on managed devices. Do not disable system security controls to install it.
