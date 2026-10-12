RAIHAN AHMAD STUDY OS — V68 PDF HIGHLIGHT ALIGNMENT FIX

What changed
- Keeps highlighting inside the existing NCERT PDF Reader panel. It does not create, export, or open a second PDF file.
- Highlights only the selected PDF text range on pointer release. Position mapping accounts for page scaling.
- Uses one annotation canvas with a fixed opacity, removing the multiply blend and stacked translucent rectangles that caused inconsistent dark/light shades.
- Retains the existing reader controls and other page content. The first activation of text-selection mode renders the same uploaded PDF into the current reader panel because a website cannot access text-selection coordinates inside the browser's private native PDF plugin.

Requirements / limitations
- Internet access is required the first time PDF.js is loaded from cdnjs.
- The PDF needs selectable text; image-only scans without a text layer cannot be word-selected without OCR.
- Highlights are kept in browser memory for the current session and are not written into the original PDF file.

Open the HTML file in a modern browser, upload the PDF, then choose “Highlight Selection” and drag across the printed text. The selected colour applies to the selected text area.
