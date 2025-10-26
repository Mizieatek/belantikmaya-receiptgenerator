
Receipt Generator — BelantikMaya
--------------------------------
Files in this package:
- index.html         : main receipt generator (open in browser)
- logo.webp / logo.svg : logo file (replace with your own logo if needed)

How to use:
1. Extract the zip and open index.html in a browser to test locally.
2. To deploy to Netlify:
   - Create a new repo (e.g., belantikmaya-receipt) and push these files.
   - Netlify: Add new site -> Import from Git -> select repo. No build command needed for static site.
   - If you want it at `https://receipt.belantikmaya.com`, add a CNAME record as instructed later.

Notes:
- The preview is scaled on-screen for convenience but print uses real A5 sizing.
- If you want direct PDF export (client-side), tell me and I can add html2pdf/jsPDF integration.
