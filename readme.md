# Innovation Model Canvas

A standalone, single-file HTML application for creating and managing Innovation Model Canvases. This tool is designed to help teams and individuals map out explorations, solutions, and potential risks in a structured, interactive format without needing complex software or internet access.

## Features

### 🎨 Interactive Canvas
- **9-Section Grid:** Standardized layout covering key areas:
  1. Ausgangslage (Initial Situation)
  2. Lösung & Hypothese (Solution & Hypothesis)
  3. Mehrwert (Value Proposition)
  4. Stakeholder / User
  5. Erfolgskriterien (Success Criteria)
  6. Perspektiven (Perspectives)
  7. Daten und Compliance (Data & Compliance)
  8. Ressourcen und Zeithorizont (Resources & Timeline)
  9. Risiken (Risks)
- **Resizable Layout:** Click and drag the grid lines to resize columns and rows to fit your content.
- **Auto-Scaling Text:** Text automatically resizes to fit within the grid cells as you type.

### 📝 Rich Text Editing
- **Floating Toolbar:** Select text to reveal a context-aware toolbar for formatting.
  - Bold, Italic, Underline
  - Ordered and Unordered Lists
- **Input Fields:** Metadata fields for Project Name, Creator, Date, and Version.

### 📌 Sticky Notes (Post-its)
- **Drag & Drop:** Drag "New Sticky Note" from the controls row onto the canvas.
- **Interactive:** Move notes freely anywhere on the canvas.
- **Editable:** Click to type comments or additional thoughts.
- **Delete:** Hover over a note and click the 'X' to remove it.

### 💾 Local Saving
- **Single File Portability:** The tool is contained entirely within one HTML file.
- **Save State:** Clicking "Save" downloads a copy of the HTML file with all your filled-in content, layout changes, and sticky notes preserved.
- **Save As:** Option to choose a specific filename (where supported).

### 🖨️ Print Friendly
- Optimizes layout for printing, hiding toolbars and controls to produce a clean version of your canvas.

## How to Use

1. **Open:** Simply double-click `innovation_model_canvas.html` to open it in your web browser. No server or installation required.
2. **Edit:** Click into any of the 9 sections to start typing. Use the top metadata fields to label your project.
3. **Format:** Highlight text to apply formatting.
4. **Annotate:** Drag the sticky note icon to add floating notes.
5. **Save:** Click the "Save (Download)" button in the top toolbar to download your work as a new `.html` file. You can open this new file later to continue editing exactly where you left off.

## Technical Details

- **Technology:** Pure HTML5, CSS3, and JavaScript.
- **Dependencies:** None. No external libraries, frameworks, or internet connection required.
- **Browser Support:** Works in all modern browsers (Chrome, Edge, Firefox, Safari).

## License

This project is open for personal and internal business use.
