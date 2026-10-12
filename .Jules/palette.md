## 2025-05-18 - Div-based interactive cards in static HTML apps
**Learning:** Custom interactive elements like `.lesson-card` and `.q-option` implemented as `<div>`s with inline `onclick` handlers lack standard keyboard navigation and focus indicators.
**Action:** Always add `tabindex="0"`, `role="button"`, and a global `keydown` listener for `Enter`/`Space` alongside `:focus-visible` CSS rules when retrofitting accessibility into static HTML apps without refactoring DOM tags.
