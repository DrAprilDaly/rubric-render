## Design Decisions

### DD-001 — Single-file deployment
The application will be distributed as a single HTML file.

Rationale:
- No installation.
- Easy distribution.
- Can operate locally.
- Avoids dependency-management requirements.

Implications:
- CSS and JavaScript are embedded.
- Icons are embedded SVG.
- Runtime CDN dependencies are prohibited.