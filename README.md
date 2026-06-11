# PocketForge Device Config

Device-side configuration for the TrimUI Smart Pro running PocketForge:

- `/etc/pocketforge/display-env.sh` (central SDL/SDL3_DYNAMIC_API/rotation environment)
- udev rules (Steam Link `56-steamlink.rules`, input device permissions)
- SDL gamepad mappings
- systemd units (`pocketforge-steamlink-kiosk.service`, `pocketforge-launcher.service`)

Produces a config tarball or `.deb` consumed by the image builder.

Populated in **Phase 1**. See the [pocketforge-os](https://github.com/pocketforge-os) org for the full repo set.
