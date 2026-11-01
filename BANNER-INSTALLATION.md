# Shared banner installation

Academic Pages does not expose one universal banner setting, so the cleanest method is to add a small shared include.

1. Copy your final banner to:

   `assets/images/turbulence-sphere-banner.jpg`

2. Create `_includes/site-banner.html` containing:

   `<div class="site-banner" role="img" aria-label="Turbulent flow structures on rotating spheres"></div>`

3. Open the layout used by the five pages, normally `_layouts/single.html` or the relevant file under `_layouts/`.

4. Insert the following immediately before the main page content:

   `{% include site-banner.html %}`

5. Import the custom stylesheet near the end of `assets/css/main.scss`:

   `@import "custom";`

If the theme's Sass load path does not find the file in `assets/css`, move `custom.scss` to `_sass/custom.scss` and keep the same import line.

The initial design uses the same image and crop on every page. If it feels too dominant, reduce `max-height` in `custom.scss` rather than creating multiple banners.
