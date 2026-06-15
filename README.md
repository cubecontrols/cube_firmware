# Cube Controls — Wheel Firmware

Official firmware downloads for Cube Controls sim racing wheels.

Every release attaches a ready-to-flash `.bin` for each supported wheel — download
the file for your model and flash it.

## Download

- **[Latest firmware](../../releases/latest)** — the current stable release.
- **[All releases](../../releases)** — full version history and release notes.

Releases marked **Pre-release** are **beta** builds. Install one only if you want
to try new features early; otherwise use the latest stable release.

## Which file do I need?

Each release includes one `.bin` per wheel, named `<model>-<version>.bin`:

| Wheel   | File                |
|---------|---------------------|
| Phoenix | `phoenix-vX.Y.bin`  |
| Astra   | `astra-vX.Y.bin`    |

Download the file that matches your wheel and the version you want.

## Versioning

Firmware is versioned `vMAJOR.MINOR` (for example `v0.18`); a higher number is
newer. Your wheel reports its installed version, so the Cube Controls app can tell
you when an update is available.

## Updating your wheel

The Cube Controls app notifies you when new firmware is available and is the
recommended way to update. To flash manually, connect the wheel over USB and load
the matching `.bin` with a standard STM32 USB-DFU tool.

## Support

Need help? Contact Cube Controls support.
