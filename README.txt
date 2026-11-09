Simon Nilsson – portfolio website

Contents
  index.html   the whole site (styles and scripts are inside)
  audio/       the music tracks (MP3)
  img/         game artwork, tool logos, FMOD screenshot and the link-preview image

To view locally: open index.html in a browser. (Some browsers block audio from local files;
if music won't play, run a small local server in this folder, e.g. "python -m http.server", and open http://localhost:8000)

To publish: upload this folder as-is (GitHub Pages, Netlify, or your web host). Keep the folder structure.

After it's live: in index.html, change the two lines
  <meta property="og:image" content="img/og-image.jpg">
  <meta name="twitter:image" content="img/og-image.jpg">
to the full address, e.g. https://simonnilsson.com/img/og-image.jpg – LinkedIn and others need the full URL to show the preview image.
