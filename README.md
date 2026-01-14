# Pixel Art Alignment Tool

A web-based tool for aligning and extracting pixel art from images. Drop an image, adjust the grid to match the pixel boundaries, and export clean pixel art.

## Features

- Drag-and-drop image loading
- Resizable grid overlay with corner and edge handles
- Adjustable N x M grid dimensions
- Grid opacity control (0%, 50%, 100%)
- Color sampling modes: center, mean, median
- Expand mode: add/remove cells while keeping cell size fixed
- Chroma key: remove background colors with tolerance slider and eyedropper
- Undo/redo support
- Keyboard shortcuts
- State persistence via localStorage
- Export to PNG at 1 pixel per cell

## Keyboard Shortcuts

- `1` / `2` / `3` - Grid opacity 0% / 50% / 100%
- `S` - Save PNG
- `X` - Toggle expand mode
- `E` - Eyedropper (pick chroma color from image)
- `C` - Toggle chroma key
- `Ctrl+Z` - Undo
- `Ctrl+Y` - Redo
- `Shift` - 10x precision when dragging
- `Ctrl` - Axis snap when dragging

## Gallery

| | | | |
|:---:|:---:|:---:|:---:|
| ![](assets/pixel_art_x55_y161_w431_h283_n68_m45.png) | ![](assets/pixel_art_x589_y133_w403_h313_n63_m49.png) | ![](assets/pixel_art_x601_y638_w396_h313_n62_m49.png) | ![](assets/pixel_art_x86_y650_w386_h302_n61_m47.png) |
| ![](assets/pixel_art_x80_y599_w352_h345_n55_m54%20(1).png) | ![](assets/pixel_art_x568_y587_w377_h364_n59_m57.png) | ![](assets/pixel_art_x98_y70_w371_h377_n58_m59.png) | ![](assets/pixel_art_x595_y64_w339_h390_n53_m61.png) |
| ![](assets/pixel_art_x72_y526_w366_h456_n57_m71.png) | ![](assets/pixel_art_x572_y552_w385_h437_n60_m68.png) | ![](assets/pixel_art_x541_y70_w450_h385_n70_m60.png) | ![](assets/pixel_art_x79_y19_w353_h450_n55_m70.png) |
| ![](assets/Gemini_Generated_Image_6wax2e6wax2e6wax.png) | ![](assets/7aTHKTANkF_00001.png) | ![](assets/dogo.png) | |

## Usage

Open `index.html` in a browser and drop an image onto the canvas.
