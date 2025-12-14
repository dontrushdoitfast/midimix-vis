# MIDImix Visualizer

A browser-based visualizer for the Akai MIDImix controller. Designed to help you memorize or plan your hardware mappings with a visually accurate, customizable interface. It's a single HTML file that you can open in any web browser on your computer.

## Features

-   **Hardware Realistic Design**: Matches the layout of the Akai MIDImix controller.
-   **Smart Grouping**:
    -   **Colored Strips**: Adjacent channels with the same color visually merge (gap removal).
    -   **Shared Headers**: Adjacent channels with the same Name share a single spanning header.
-   **Interactive Labeling**:
    -   Click any text label to rename it inline.
    -   **Shift+Click** a merged header to split it back into individual columns.
-   **Discrete Color Picker**: Click the small LED next to the channel name to open the hidden color palette.
-   **Setup Management**: Download and Upload your configurations as JSON files.
-   **Offline Ready**: Zero dependencies, runs entirely in the browser from a single HTML file.

## How to Use

1.  **Open**: Simply drag `index.html` into any modern web browser or open from the "Open" option in the File menu.
2.  **Edit**: Click on any knob label, fader label, or button text to rename it (max 12 chars).
3.  **Group**:
    -   Rename adjacent headers to the same text (e.g., "DRUMS") to merge them.
    -   Set adjacent strips to the same color to remove the gap between them.
4.  **Save**: Click "Save JSON" to backup your mapping layout.

## Customization

The visualizer is styled to match a specific custom MIDImix unit:
-   **Knobs**: Row 1 (Black), Row 2 (Wood/Tan), Row 3 (White).
-   **Buttons**: Unlit white plastic style (high contrast).
-   **Chassis**: Matte dark grey with screw details.

## Tech Stack

-   **Core**: HTML5, CSS3, ES6+ JavaScript.
-   **Libraries**: React 18, Babel Standalone (loaded via CDN for single-file portability). Created using Google Anti Gravity - I didn't write any code and it took a few hours of back and forth, starting with a stock image of the midmix.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Copyright (c) 2025 Henry Chin (@dontrushdoitfast).
