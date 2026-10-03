FLEXIBILITY PASSPORT — YUVVA YODHA PITCH DECK (EDITABLE HTML)
=============================================================

CONTENTS OF THIS PACKAGE
------------------------
1. Flexibility_Passport_Deck_Editable.html
   -> ONE self-contained file with all 14 slides stacked vertically.
      Easiest way to view / present / edit: just double-click it.

2. slide_01.html ... slide_14.html
   -> The same 14 slides as individual files (one slide per file,
      1280 x 720 px each). Best for fine-grained editing.

3. global.css
   -> The shared Eco-Brutalist design system (colors, fonts, panels,
      hard shadows, hazard stripes, stamps, barcodes).
      slide_01..14.html link to this file — keep it next to them.

4. slides_brief.json
   -> Content + layout map of every slide, including the per-slide
      PowerPoint animation recipes (Morph / staggered fade / wipe etc.)
      if you rebuild the deck in PowerPoint.

HOW TO EDIT
-----------
- Any text: open a slide in VS Code / Notepad++ / any editor and edit
  the HTML directly. All content is plain text in the markup.
- Colors / fonts: edit the CSS variables at the top of global.css
  (--bg, --ink, --green, --mint, --butter, etc.).
- Fonts are loaded from Google Fonts (Anton, Space Grotesk, Inter,
  Space Mono) — an internet connection is needed on first load.
- The 3 photos are loaded from a CDN; to swap them, replace the
  <img src="..."> URL in slide_01, slide_02 and slide_04.
- Team names are placeholders (TEAM NAME / member slots) — search for
  "TEAM" and replace before submitting.

HOW TO PRESENT FROM HTML
------------------------
- Open Flexibility_Passport_Deck_Editable.html in a browser,
  press F11 for full screen, scroll = next slide.
- Or print each slide to PDF from the browser (1280x720 landscape).

HOW TO GET IT BACK INTO POWERPOINT
----------------------------------
- Use the already-generated Flexibility_Passport_YuvvaYodha_PitchDeck.pptx
  (in the same download folder), which contains the rendered slides
  plus speaker notes with step-by-step PowerPoint animation recipes.

SUBMISSION CHECKLIST (Hackathon)
--------------------------------
[ ] Replace TEAM NAME + member name placeholders (slide 1 & 14)
[ ] Fill the X kW / Y min / Z ramp figures with your pilot's real data
    (slide 4, 6, 12) if they differ from the defaults used here
[ ] Rehearse with the animation notes in slides_brief.json
