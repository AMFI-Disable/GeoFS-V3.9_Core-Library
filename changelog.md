# Changelog

All notable changes, architectural utilities, and version releases for GeoFS-V3.9 Core Library are documented in this file.

---

## [3.9.0] - Unified Metadata

### Changed

- Standardize the userscript metadata and version across the V3.9 ecosystem.
- Match only the GeoFS main site and activate only when it reports V3.9.

---

## [Unreleased]

### Changed

- **HUD Tab Order**: Keep Information, Fuel, Checklist, and Realism tabs in a consistent order and size the row to the modules present.
- **Notification Toast System**: Redesigned `V39_NOTIF` notification toasts with rounded styling, neutral `#dddddd` borders, and consolidated individual addon startup messages into a single ready notice.
- **HUD Theme Alignment**: Standardized HUD styling, drag handles, labels, and active tab highlights to neutral tones (`#dddddd`).
- **Favicon Metadata**: Switched userscript icon reference to the official GeoFS favicon.

---

## [2.0.14] - GeoFS V3.9 Compatibility

### Changed

- Start only after GeoFS reports V3.9; remain inactive on other or unrecognized versions.
- Update compatibility documentation and version metadata.

---

## [2.0.13] - Startup Panel and Notification Banners

### Changed

- Keep the startup panel open when scripts are not detected or fail, and dismiss it after all scripts are detected.
- Show in-flight messages as separate temporary banners.

---

## [2.0.12] - Legacy Startup Notification Fix

### Fixed

- Suppress the old emoji Core Library startup toast from cached dependencies while keeping the shared ecosystem panel.

---

## [2.0.11] - Unified Core Startup

### Fixed

- Report Core Library startup in the shared panel without a separate legacy toast.
- Replace earlier versions of the shared notification engine.

---

## [2.0.10] - Notification Header Compatibility

### Fixed

- Replace cached versions of the notification panel so the new header appears.

---

## [2.0.9] - Ecosystem Notification Header

### Changed

- Renamed the shared notification panel header to GeoFS-V3.9_Ecosystem.

---

## [2.0.8] - Startup Detection Fix

### Fixed

- Detect add-ons that started before the status panel and keep checking during startup.
- Replace older notification engines to avoid losing module reports.
- Wait for startup to settle before listing add-ons that were not detected.

---

## [2.0.7] - Unified Startup Status

### Changed

- Combined startup status, missing-module notices, and runtime notifications in one dismissible panel.
- Kept flight warnings visible in the same panel.

---

## [2.0.1] - Error Boundary Wrappers And Draggable Engine

### Added

- **Universal Draggable UI Helper**: Shared DOM manipulation utility allowing any module window or button to be repositioned with viewport boundary enforcement.
- **SafeInit Module Wrapper**: Fault-tolerant initialization wrapper ensuring isolated module errors do not crash adjacent simulation services.

### Fixed

- **LocalStorage State Resilience**: Guarded against storage quota errors and corrupted JSON schemas during position restoration.
- **Flight Simulator Lifecycle Hooks**: Cleaned up simulator event listener attachment and aircraft change triggers.

---

## [2.0.0] - Unified Ecosystem API

### Added

- **Centralized Event Dispatcher**: Inter-addon messaging pipeline for sharing airspeed, fuel states, and failure alarms.
- **Standard Telemetry Readers**: Standardized getters for Cesium eye positions, true airspeed, and orientation quaternions.

---

## [1.0.0] - Initial Production Release

Initial release of foundational utilities and shared runtime routines for GeoFS-V3.9.
