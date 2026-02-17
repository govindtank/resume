# resume-template (customized for Govind Tank)

This repository is a Jekyll + GitHub Pages resume for Govind Tank. It has been customized to include an updated professional summary, technical skills, experience and an A4 printable stylesheet for PDF export.

## Local testing

1. Clone the repo:
   git clone <repo-url>
2. Change into the repo:
   cd resume
3. Install dependencies:
   bundle install
4. Run locally:
   bundle exec jekyll serve
5. Open:
   http://localhost:4000

## What changed in this branch
- Updated _config.yml with new header, contact, and professional summary.
- Added a custom resume layout at `_layouts/resume.html`.
- Added `css/print.css` — A print-focused stylesheet for A4 PDF export.
- Updated README to include PDF/export instructions.

## Exporting to PDF (print-friendly)
1. Open the site locally (or the live GitHub Pages URL) in Chrome.
2. Use the browser Print dialog (Ctrl/Cmd+P).
3. Set Destination to "Save as PDF".
4. Under More Settings:
   - Paper size: A4
   - Scale: default (adjust if needed)
   - Margins: Default (or set to Minimum)
   - Ensure Background graphics is checked for consistent rendering
5. Save. The layout is tuned to produce a clean A4 PDF.

## Notes
- Customize further by editing `_config.yml` and `_layouts/resume.html`.
- To change which sections are displayed, toggle the `resume_section_*` flags in `_config.yml`.
