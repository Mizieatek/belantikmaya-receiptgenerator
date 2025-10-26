
Receipt Generator — BelantikMaya (PDF-ready)
--------------------------------------------
Files:
- index.html : Receipt generator with 'Muat Turun PDF' using html2pdf.js
- logo.webp  : logo (replace if needed) / logo.svg fallback

Usage:
1. Extract files and open index.html to test locally.
2. Fill form, then click 'Muat Turun PDF' to generate A5 PDF that matches preview.
3. To deploy to Netlify, create a repo and push these files. No build required for static site.

Notes:
- html2pdf renders the preview element to canvas then to PDF. Ensure logo is accessible (CORS) if loading from remote URL.
- If you need server-side perfect fidelity (fonts/kerning), consider Puppeteer or wkhtmltopdf.
