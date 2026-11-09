Screenshots for openzim/cms#638 demo page.

Rendered by calling the PR's own `build_collection_demo_html` directly on synthetic collection entries (no database, no running backend), then loading the emitted HTML in headless Chrome 156.

- `desktop.png` - 1440px viewport, six books: Download + Browse, one book without Browse (transition_status set), one without an illustration.
- `nobrowse.png` - same page with `view_base_url` unset, so Browse is absent everywhere.
- `mobile.png` - 414px viewport; the table is 710px wide, so Details and Links fall outside the screen.
