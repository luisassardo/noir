# Changelog

## Unreleased

### Fixed

- Email signup forms: the "Enter your email" label rendered on top of the input because the `.gh-sr-only` (screen-reader-only) rule was missing from the stylesheet. The label is now visually hidden and still available to assistive technology.

### Changed

- README now carries a screenshot gallery; the hosted demo (noir.quicktheme.online) was retired.
- `package.json` author URL now points to luisassardo.com instead of the retired demo domain.

## 1.0.0 — 2026-03-16

### Initial release

- Dark editorial theme with teal (#0dd9a3) accent
- Plus Jakarta Sans typography
- Custom 5-row homepage layout:
  - Hero featured post
  - Featured posts grid (3 columns)
  - Subscribe CTA for non-members
  - Opinion tag section (4 columns)
  - Latest posts feed with automatic de-duplication
- Full Ghost feature support:
  - Members & subscriptions
  - Native search (Ghost Search)
  - Comments
  - Recommendations
  - Newsletter signup forms
- 5 header styles: Landing, Highlight, Magazine, Search, Off
- Grid and List feed modes
- 17 custom settings configurable from Ghost Admin
- Tag and author archive templates
- Error page template (404/500)
- Lightbox with PhotoSwipe
- Infinite scroll pagination
- Full Ghost editor card styling
- 13 language files (including Spanish)
- Responsive design, mobile-first
- Keyboard navigation and accessibility support
- Based on Ghost Source theme architecture
