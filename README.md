# The Seven Summits

Live site: https://sevensummits.netlify.app/

```
RUN LOCALLY

  python3 -m http.server 8000

  Then open http://localhost:8000
  A local server is required; opening index.html directly won't load the .glb models.


PROJECT STRUCTURE

  index.html     the whole site: layout, styles and code
  lib/           the model-viewer library and the font, stored locally so the site works offline
  models/        one .glb 3D model per mountain

  To change any mountain names, locations or heights, edit the PEAKS list near the bottom of index.html.

  i love the appearance of the readme in a code block
```
