# Changelog

## [0.1.8] — 2026-05-11

### ✨ Added

#### Core
- Implemented the core components of the `D3` ecosystem:
    - `Studio`
    - `Hub`
    - `Runtime`
    - `Engine`

#### Studio
- Implemented the basic UX/UI infrastructure of the workspace
- Implemented project and aggregator management
- Implemented interactive simulations based on `CandleStick` data
- Implemented application settings
- Experimentally integrated the `LightweightCharts.Blazor` library

---

## [0.2.18] — 2026-05-22

### ✨ Added

#### Hub
- Added dataset management support to the `Hub` user interface
- Implemented OHLC chart rendering based on dataset data
- Added a dataset data loading mechanism for chart visualization

#### DatasetService
- Implemented `D3.DatasetService` — a component for managing dataset data
- Added basic scenarios for connecting to storage and working with dataset data

#### Documentation
- Added technical documentation infrastructure based on `DocFX`

### ♻️ Changed

#### Studio
- Updated and improved the main user interface of the system
- Improved the structure of user components and workspaces

#### Engine
- Reworked the prototype of the data processing and analysis engine

### 🐛 Fixed

- Fixed issues identified in the previous version

## [0.3.39] — 2026-06-07

### ✨ Added

#### Engine

* Implemented the basic data processor mechanism
* Added support for processor execution within runtime sessions
* Added infrastructure for storing and retrieving processor results

#### Runtime

* Implemented interactive data simulation mechanisms
* Added support for step-by-step simulation based on dataset data
* Added separate runtime execution contexts for viewer and simulation scenarios

#### Studio

* Expanded workspace UI functionality
* Added interactive simulation controls
* Added support for switching between viewer and simulation modes
* Added UI state synchronization for runtime sessions and chart interactions

#### Hub

* Updated the Hub interface
* Added ordering support for projects, aggregators, storage connections, and datasets
* Added reorder API endpoints and client methods for ordered entities

### ♻️ Changed

#### Engine

* Optimized data window behavior and data loading flow
* Improved runtime data handling for simulation and viewer scenarios

#### Studio

* Improved chart behavior and viewport handling
* Refined workspace layout and navigation behavior
* Improved drag-and-drop ordering behavior for UI collections

#### Hub

* Improved project, aggregator, storage connection, and dataset ordering consistency
* Updated API contracts and clients for reorder operations

### 🐛 Fixed

#### Studio

* Fixed UI issues related to chart state, viewport updates, and list refresh behavior
* Fixed ordering loss in client-side mappings for aggregators, storage connections, and datasets

#### DatasetService

* Fixed analyzer warnings and improved culture-invariant parsing for `TimeSpan` tick values
