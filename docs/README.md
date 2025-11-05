# NemoPresetExt Documentation

This directory contains comprehensive documentation for the NemoPresetExt extension.

## Available Documentation

### [presets-integration.md](./presets-integration.md)
**Primary Documentation:** Complete analysis of how NemoPresetExt integrates with and manipulates Chat Completion presets in SillyTavern.

**Contents:**
- Architecture overview with flow diagram
- Entry points and responsibilities with file:line references  
- Data models and storage locations
- Event/observer wiring details
- Preset application mechanism explanation
- Import/export flows documentation
- Favorites system implementation
- Snapshots and archives functionality
- Development notes and extension points
- Settings and configuration reference

## Documentation Purpose

This documentation serves to:
- Explain the extension's integration approach with SillyTavern's preset system
- Provide developers with understanding of preset manipulation mechanisms
- Document all preset-related code paths and data flows
- Offer guidance for extending or hooking into preset functionality
- Serve as reference for maintenance and troubleshooting

## Key Insights

The extension uses a **non-invasive integration approach**:
- Observes DOM changes to detect preset UI elements
- Enhances existing UI rather than replacing it
- Manipulates preset selection through standard DOM events
- Stores extension data separately from core preset data
- Leverages SillyTavern's native APIs for all preset operations

This ensures compatibility with SillyTavern updates while providing rich preset management capabilities.
