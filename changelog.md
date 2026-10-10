# Changelog

All notable changes, architectural utilities, and version releases for GeoFS-V3.9 Core Library are documented in this file.

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
