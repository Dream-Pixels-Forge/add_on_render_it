# Render It - Blender Addon

## Overview
Render It is a comprehensive rendering toolset for Blender that provides a compact and efficient interface for managing render settings and presets. This addon streamlines the rendering workflow by offering quick access to commonly used rendering features and settings.

## Features

### Quick Actions
- One-click render and animation rendering
- Instant access to render settings
- Quick viewport and final render toggles

### Resolution Management
- Easy resolution switching with predefined scales (25%, 50%, 75%, 100%, 150%, 200%)
- Quick resolution swapping (width/height)
- Reset to default resolution
- Visual resolution scale presets

### Sampling Presets
- Quick sampling presets for Cycles renderer:
  - Preview (128 samples)
  - Low (256 samples)
  - Medium (512 samples)
  - High (1024 samples)
  - Ultra (2048 samples)
  - Maximum (4096 samples)

### Output Management
- Customizable output path
- Automatic subfolder creation
- Date-based organization
- Project-based rendering structure
- Quick access to render folders

### Render Presets
- Save and load render configurations
- Manage multiple render presets
- Easy preset switching
- Preset organization tools

## Installation

1. Download the addon ZIP file
2. Open Blender and go to Edit > Preferences
3. Click on the "Add-ons" tab
4. Click "Install" and select the downloaded ZIP file
5. Enable the addon by checking the checkbox next to "Render: Render It"

## Configuration

### Addon Preferences
- **Project Name**: Set default project name for organizing renders
- **Default Resolution**: Configure default render dimensions
- **Output Settings**: 
  - Default output path
  - Auto-save options
  - Subfolder organization
  - Render time display

## Usage

### Accessing the Panel
The Render It panel can be found in:
- Properties Editor > Render Properties > Render It

### Quick Actions
1. Use the "Render" button for single frame renders
2. Use the "Animation" button for sequence rendering
3. Access quick sampling presets for different quality levels

### Managing Presets
1. Create new presets using the "+" button
2. Select and apply presets from the preset list
3. Organize presets using up/down arrows
4. Remove unwanted presets using the "-" button

### Resolution Control
1. Use preset scale buttons for quick resolution adjustments
2. Swap dimensions using the swap button
3. Reset to default using the reset button

## Compatibility
- Blender Version: 4.2.0 and above
- Operating Systems: Windows, macOS, Linux

## Known Issues
- Resolution presets are limited to predefined scales
- Cycles-specific features won't work with Eevee renderer

## Support
For issues, suggestions, or contributions, please contact the developer:
- Author: Dimona Patrick

## License
[SPDX:GPL-3.0-or-later]

## Version History
- 1.0.2: Current release
  - Added preset management system
  - Improved UI layout
  - Enhanced output management
