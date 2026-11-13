Drop brand logo files in this directory to display them on /coaching.

Expected filenames (any of these extensions work: .png, .svg, .jpg, .webp):
  maju-superfoods.png
  goli.png
  medicube.png
  jiyu.png
  m3-naturals.png
  physicians-choice.png
  dude-wipes.png
  my-peeps.png
  sinless-snacks.png
  tru-height.png
  questions-about-me.png
  zok-relief.png

Notes:
- The coaching page links to /brands/{slug}.png (PNG by default).
- If you have SVGs instead, update the src in packages/faceless-landing/src/pages/coaching.astro (line that reads `/brands/${b.slug}.png`).
- Recommended: transparent background, 200–400px tall, mono-tone if the brand has a wordmark.
- If a logo file is missing, the card falls back to a clean text tile automatically.
