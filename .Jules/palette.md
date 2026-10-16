# Palette's Journal - Critical Learnings

## 2025-02-17 - Keyboard Navigation for Card Grids
**Learning:** In custom card-based navigation grids (such as clickable `<div>` cards without `<a>` or `<button>` wrappers), screen reader and keyboard users cannot focus or activate options using standard Tab/Enter/Space controls unless `role="button"`, `tabindex="0"`, focus indicators, and `keydown` event listeners are explicitly provided.
**Action:** When working with custom card layouts, always add `role="button"`, `tabindex="0"`, `:focus-visible` ring/outline CSS, and `keydown` listeners for Enter/Space key presses.
