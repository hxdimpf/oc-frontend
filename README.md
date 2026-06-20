# OC Frontend

Shared JavaScript modules, CSS, and vendor libraries for OC4 (Symfony) and OC5 (Node.js).

## Usage

Add as a git submodule at `public/_frontend/`:
```
git submodule add https://github.com/hxdimpf/oc-frontend.git public/_frontend
```

Then reference in templates:
```html
<script type="module" src="/_frontend/js/loader.js"></script>
<link rel="stylesheet" href="/_frontend/css/oc-style.css">
```

## Structure
- `js/` — ES modules (loader, cache, map, i18n, etc.)
- `css/` — Stylesheets
- `vendor/` — Third-party libraries (Bootstrap, Tabulator, Leaflet)
