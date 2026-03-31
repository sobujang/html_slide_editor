# HTML Slide Editor (슬라이드 편집기)

A professional-grade, web-based presentation tool featuring a Figma-inspired interface for creating and managing HTML-based slides. 

## ✨ Key Features

- **🎨 Figma-Inspired UI**: Modern dark-themed interface designed for high productivity and professional aesthetics.
- **🗂️ Dynamic Slide Management**: Easily add, duplicate, delete, and reorder slides using the intuitive thumbnail strip.
- **🖱️ Powerful Element Editor**:
  - **Canvas Interaction**: Drag-and-drop positioning with smart snapping.
  - **Inline Editing**: Double-click to edit text directly on the canvas.
  - **Precision Selection**: Multi-element selection with Lasso and modifier keys (Shift/Ctrl).
  - **Property Controls**: Fine-tune colors, opacity, shadows, borders, and more in the property panel.
  - **Layer Logic**: Advanced z-index control and layer organization.
- **📤 Advanced Import/Export**:
  - **Import**: Seamlessly load HTML files, raw code, or multi-slide structures (supporting Reveal.js sections).
  - **Export**: Generate high-quality **PPTX**, **PDF**, or **PNG** files with a single click.
- **⚡ Productivity First**:
  - **Auto-Save & Recovery**: Automatic persistence to local storage to protect your work.
  - **History (Undo/Redo)**: Complete state management with standard shortcut support.
  - **Keyboard Mastery**: Industry-standard shortcuts for copying, pasting, duplicating, and nudging.
  - **Visual Aids**: Zoom controls (Fit/In/Out), alignment grid, and aspect ratio switching (16:9 / 4:3).

## 🚀 Getting Started

### Prerequisites
The editor is a standalone, browser-based application. No installation is required.

### How to Use
1. Open `html_slide_editor.html` in any modern web browser.
2. **Create/Load**: Use the sidebar to add new slides or the **"Import"** button to load base HTML.
3. **Design**: Select elements on the canvas to modify them or use the "Edit Code" tab in the property panel for direct HTML/CSS manipulation.
4. **Finalize**: Use the top toolbar to export your project into your preferred format.

## 🛠️ Built With

- **Vanilla JS/HTML/CSS**: Core logic and high-performance UI components.
- **[PptxGenJS](https://gitbrent.github.io/PptxGenJS/)**: Professional PowerPoint generation.
- **[html2canvas](https://html2canvas.hertzen.com/)**: High-fidelity slide previews and image rendering.

## 🎹 Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + Z` / `Ctrl + Y` | Undo / Redo |
| `Ctrl + S` | Manual Save |
| `Delete` | Delete Selected Element |
| `Ctrl + C` / `Ctrl + V` | Copy / Paste Element |
| `Ctrl + D` | Duplicate Element |
| `Arrow Keys` | Move Element (1px nudge) |
| `Shift + Arrow Keys` | Move Element (10px jump) |

---
*Built for modern presentation workflows.*
