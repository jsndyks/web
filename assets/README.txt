jdScrawl — webfonts

1. Copy jdscrawl.css and the fonts/ folder together into your
   website's public/static assets, keeping their relative directory structure.
2. Link the stylesheet in the HTML head.
3. Apply class="jdscrawl" or set font-family: "jdScrawl".
4. Choose CSS font-weight 300 (Light), 400 (Regular), 600 (SemiBold),
   700 (Bold), or 900 (Black).
5. Keep contextual alternates and kerning enabled for the natural variations.
   Do not use text-transform: uppercase; lowercase input already maps to
   all-capital glyphs and provides alternate forms. Capitalised source input
   does not automatically change weight. Use strong or explicit font-weight
   for emphasis. Black includes an intrinsic 120% glyph scale.
6. index.html is a standalone local specimen/test page. If your browser won't
   load local font files when opened directly, serve the folder from your
   site's web server (or run python3 -m http.server 8000 in it).

WOFF2 conversion verified by reading each converted font and checking its
character map and GSUB/GPOS tables. Browser support of contextual features
may vary. The font currently covers A-Z, numbers and selected punctuation.

Version 0.14 gives every forward-slanting 1 a top and foot and every 9
a leftward bottom foot. Other forms are retained. Contextual variation is retained, and
three typed periods form an ellipsis when standard ligatures are enabled.
