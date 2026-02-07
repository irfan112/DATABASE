INTRODUCTION TO DATABASES — One-page PDF
=========================================

This folder contains everything for your one-page database introduction (for your book).

WHAT'S HERE
-----------
• Introduction-to-Databases.pdf   — One-page PDF (already generated).
• introduction-to-databases.html — Same content as HTML; open in a browser and use File → Print → Save as PDF if you want to tweak layout or print from the browser.
• assets/                        — Your three figures (Fig. 1: data to files, Fig. 2: sources to database, Fig. 3: query/SQL/result).
• generate_pdf.py                — Script to regenerate the PDF (run: python generate_pdf.py). Requires: pip install reportlab.

HOW TO REGENERATE THE PDF
-------------------------
  pip install reportlab
  python generate_pdf.py

The PDF will be overwritten as Introduction-to-Databases.pdf.

ALTERNATIVE: PDF FROM HTML
--------------------------
Open introduction-to-databases.html in Chrome or Edge, then File → Print → Destination: Save as PDF → Save. The page is set up for A4 and should fit on one page.
