# Copilot instructions (MoiBook site)

## Project snapshot
- Static, single-page marketing site in plain HTML. Main entry: index.html.
- No build, test, or runtime tooling detected. Changes are direct edits to HTML/CSS.
- External dependency: Google Fonts (Noto Sans Tamil) via <link> in the head.

## Architecture & structure
- Single page layout with semantic sections: topbar, hero, feature grid, form card, footer.
- Page wrapper: .page → .topbar + .container; content flows top to bottom.
- Components are expressed as HTML sections with class-based styling (e.g., .hero-card, .form-card, .card, .footer).

## Conventions and patterns (use these)
- Maintain bilingual Tamil/English labels (e.g., “MoiBook / மொய்புக்”, “Book Now”, “Contact”).
- Preserve semantic HTML tags (header, main, section, article, footer).
- Class naming is descriptive and flat (no BEM): topbar, hero-card, form-card, card-body, section-title, footer-logo.
- Buttons use class tokens for styling: .primary, .full, .pill, .chip, .back.

## Styling notes
- index.html expects a stylesheet at styles.css. If you add or change classes, update/create styles.css accordingly.
- Typography should stay Tamil-friendly; continue using the Noto Sans Tamil font or compatible fallback.

## Working approach
- Edit index.html directly for content/structure updates.
- When adding new sections, follow the existing pattern: section title → grid of cards or a single card block.
- Keep copy concise and aligned with the “Digital tradition” theme.
