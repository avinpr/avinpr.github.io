========================================
Treasures of the Past — eBook Package
========================================

Title: Treasures of the Past
Subtitle: The hidden secrets of Native-Americans
Compiled by: Team Lego Legends

Package Contents
----------------
- index.html       → The eBook pages (cover + one page per artifact)
- styles.css       → Styles for layout, colors, borders, and print
- images/          → All images used by the eBook
    • cover.jpg
    • quill-basket.jpg
    • arrowhead-aayush.jpg
    • fur.jpg
    • fishing-net.jpg
    • turtle-rattle.jpg
    • symbols.jpg
    • shell-necklace.jpg
    • drums.jpg
    • pottery.jpg
    • arrowhead-sidak.jpg
    • clothing.jpg
    • baskets.jpg

How to Use
----------
1) Place all files exactly as shown above. Keep file names and folder names the same.
2) Open index.html in any modern browser (Chrome, Edge, Safari, Firefox).
3) Scroll to view one landscape “page” per artifact. Images appear beside the story text.
4) To export as PDF:
   - Browser menu → Print… 
   - Destination: “Save as PDF”
   - Layout: Landscape
   - Margins: Default (or None if you want full-bleed)
   - Options: Enable “Background graphics” (so colors/borders print)
   - Save

Editing / Customizing
---------------------
• Text: Open index.html in a text editor and edit the story text or headings.
  NOTE: The student stories are included exactly as provided; please keep them unchanged if that’s required.
• Colors: Each page theme color is defined in styles.css (search for .theme-* classes).
• Borders: The decorative border is a repeating gradient in styles.css under `.bordered`.
• Fonts: Titles use a handwritten/craft vibe via common fonts:
  - "Comic Sans MS", "Bradley Hand", "Segoe Print"
  Body uses: Calibri/Arial. Your system will fall back if not installed.

Images
------
• Save the provided images into the /images folder using the exact file names listed above.
• To replace an image, keep the same file name and overwrite it.
• Recommended sizes: 1600–2000px wide .JPG for best results (already optimized for the layout).

Accessibility Tips
------------------
• All images include descriptive alt text (edit in index.html if needed).
• Increase body font size in styles.css by adjusting `.story { font-size: 18px; }`.
• Ensure sufficient color contrast if printing for public display.

Troubleshooting
---------------
• Images not showing:
  - Check that the /images folder sits next to index.html.
  - Confirm file names and extensions match exactly.
• Colors missing in PDF:
  - In the Print dialog, enable “Background graphics”.
• Page breaks in print:
  - A page is one <section class="page">. Printing uses CSS @media print with page breaks.
  - If a page spills to the next sheet, reduce story font size slightly or scale during print (90–95%).
• Landscape not applying:
  - In the Print dialog, choose “Landscape” and ensure “Fit to page” is enabled.

File Integrity
--------------
• Keep the folder structure unchanged:
  Treasures_of_the_Past_eBook/
    - index.html
    - styles.css
    - images/

Credits & Notes
---------------
• Design: School-project style with bright colors, simple geometric borders, and image-beside-text layout.
• Images: Artistic renderings generated for this project. Replace only if needed, keeping filenames.
• Educational Use: Content assembled for classroom/heritage learning.

Contact / Maintenance
---------------------
• To add more artifact pages: Duplicate one <section class="page"> in index.html,
  update student/artifact labels, image path, and choose a theme color class.
• For a different title/subtitle/compiler line, edit the Cover section near the top of index.html.

Enjoy your eBook!
