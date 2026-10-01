# CACALE.IO v10 — Forced Mobile Keyboard Position

The mobile keyboard and action buttons now use high-specificity fixed positioning with
`!important` overrides so earlier layout rules cannot push them below the visible screen.

- Keyboard fixed above Safari's bottom toolbar area.
- Actions fixed beneath the keyboard.
- Safe-area aware.
- POPO target unchanged.
- Hint scoring and POPO celebration unchanged.
- Service worker cache bumped to v10.
