## 2025-10-09 - Focus Visible & Keyboard Navigation for Custom Non-Semantic Controls
**Learning:** In static single-page applications built without native `<button>` or `<a>` elements for cards and options, custom interactive elements (`div.lesson-card`, `div.q-option`) are inaccessible via keyboard navigation and lack focus indicators.
**Action:** Always complement custom `onclick` handlers with `tabindex="0"`, `role="button"`, `aria-label`, and `onkeydown` (supporting `Enter` and `Space`) alongside `:focus-visible` CSS rules for high contrast focus rings.
