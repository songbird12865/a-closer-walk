A CLOSER WALK — CONSOLIDATED WEBSITE PAGES

Copy the CONTENTS of this ZIP into the ROOT of your existing a-closer-walk GitHub Pages repository. Merge folders; do NOT delete or replace existing assets folders.

Included:
  365dayswithgod/ (existing styled pages, logo and clean URLs)
  bible-crossword/ (styled homepage, support and privacy, CSS)
  faith-trails/ (styled homepage, support and privacy, CSS)
  support/index.html (existing shared support page, updated links)
  bible-crossword-privacy.html (legacy URL retained for existing links)

IMPORTANT:
- Keep your existing bible-crossword/assets/ and faith-trails/assets/ folders; they contain actual logos and screenshots referenced by the homepages. They are NOT in this ZIP.
- Keep the existing PythonAnywhere /privacy page running or redirect it to https://acloserwalk.org/faith-trails/privacy/; this ZIP does not modify PythonAnywhere.
- Keep old privacy URL https://acloserwalk.org/bible-crossword-privacy.html functioning.
- Check Faith-Trails policy statement about game database against current device-local storage implementation before publishing. This ZIP preserves the supplied policy wording.
- Review actual app behavior and privacy declarations before changing App Store Connect links.
- Faith-Trails homepage still contains original pre-release App Store wording; update if now published.
- Existing website root index.html, apps.html, and other app pages are not replaced.

PowerShell from repository root after copying:
 git status
 git add 365dayswithgod bible-crossword faith-trails support bible-crossword-privacy.html
 git commit -m "Consolidate app website pages"
 git push origin main

URLs:
 https://acloserwalk.org/bible-crossword/
 https://acloserwalk.org/bible-crossword/support/
 https://acloserwalk.org/bible-crossword/privacy/
 https://acloserwalk.org/faith-trails/
 https://acloserwalk.org/faith-trails/support/
 https://acloserwalk.org/faith-trails/privacy/
 https://acloserwalk.org/365dayswithgod/
 https://acloserwalk.org/support/
