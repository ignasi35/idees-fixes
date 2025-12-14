# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website project called "Idees fixes" - resources and examples for parent associations (AFAs) and entities in favor of de-digitizing childhood. The website is built using the Stellar template from HTML5 UP.

## Architecture

- **Static HTML Site**: No build process required
- **Template**: Based on Stellar by HTML5 UP (CCA 3.0 license)
- **Styling**: SASS source files in `assets/sass/` compile to `assets/css/main.css`
- **JavaScript**: jQuery-based with Scrollex plugin for sticky navigation
- **Main Pages**:
  - `index.html` - Main landing page with sections for Introduction, Pantalles, Torna el Fixe, Comerç Amic
  - `generic.html` - Generic page template
  - `elements.html` - UI elements showcase. This is not a real user-facing page and this should not be edited ever.
  - `comerc_amic.html` - New page (currently being developed)

Because these HTML files are static, make sure any edits on the footer of `index.html` are replicated in other pages as needed (except `elements.html`).
Also check that there are no broken links between pages.

## Development

### SASS Compilation
If modifying styles, compile SASS files from `assets/sass/` to generate `assets/css/main.css`. Note: No SASS compiler is currently configured in the project.

### Local Preview
Open HTML files directly in a browser or use a simple HTTP server:
```bash
python3 -m http.server 8000
```

## Key Dependencies

- jQuery (assets/js/jquery.min.js)
- Scrollex plugin for sticky navigation
- Font Awesome icons (assets/webfonts/)
- Breakpoints.js for responsive behavior
