# GeoFS-V3.9_Core-Library

![Version](https://img.shields.io/badge/Version-v3.9.0-3b82f6?style=flat-square)

Provides shared initialization, notification, HUD, and utility functions for the GeoFS-V3.9 scripts.

## Features

- The **GeoFS-V3.9_Ecosystem** startup panel closes when all add-ons are detected. If any are missing or fail to start, it stays open and identifies them; select × to dismiss it. Runtime messages appear as separate temporary banners.
- Add-ons that are not detected may be uninstalled, disabled, still loading, or unable to start.
- Provides the shared HUD tabs and initialization error handling used by other scripts.

## Installation

1. Install a userscript manager such as [Tampermonkey](https://www.tampermonkey.net/).
2. Install or update the script from [Greasy Fork](https://greasyfork.org/en/scripts/581510-geofs-v3-9-core-library).
3. Open or reload GeoFS V3.9. The script starts automatically.

The script activates only when GeoFS reports version V3.9 (including V3.9 patch releases). It waits for the version to become available and remains inactive on other versions. Most standalone scripts load the Core Library and Design System as dependencies; the userscript manager handles those dependencies.

A script listed as not detected may be uninstalled, disabled, or still loading.

## License

[MIT](license) · © 2026 AMFI-Disable · [GeoFS-V3.9 Ecosystem](https://sites.google.com/view/geofs-v39-ecosystem/home)
