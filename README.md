# <img src="./logo.svg" width="40" vertical-align="middle"> Iris Annotator

A fast, fully-local, rule-based utility for batch annotating and stripping PDFs.

Iris lets you define search phrases, exact matches, and regular expressions to automatically apply highlights and sticky notes to hundreds of pages in seconds.

**[Launch Iris Annotator](https://seumas.github.io/Iris-Annotator/)**

## 🚀 Features
- **Rule-Based Highlighting:** Define custom rules (Partial, Exact Word, or Regex) with specific colors and sticky notes.
- **Batch Processing:** Drag and drop multiple PDFs to process them all at once.
- **Selective Stripping:** Safely remove all existing annotations, or surgically strip them based on the author's name or highlight color (preserves links and form fields).
- **Workspace Profiles:** Save your rule setups and output settings. Export/import profiles as JSON to share with editors or backup your workflow.
- **Extraction Reports:** Copy a detailed clipboard summary of exactly what was found and on what pages.
- **100% Private:** No backend. No cloud. Files are processed entirely in your browser's local RAM.

## 🛠️ How to Use
1. **Add Rules:** Enter terms you want to find. Use the magic wand for common Regex presets (Emails, Phone Numbers, Dates).
2. **Queue Files:** Drag and drop your PDFs into the app.
3. **Process:** Click "Annotate Files" (or "Strip Annotations").
4. **Save:** Preview the results directly in your browser, copy your extraction reports, and save the finalized PDFs.

## 🔒 Privacy & Security

Iris Annotator is a static, client-side application. Your documents **never** leave your device. The heavy lifting is done using your browser's local memory via [PDF.js](https://mozilla.github.io/pdf.js/ "null") and [pdf-lib](https://pdf-lib.js.org/ "null").
