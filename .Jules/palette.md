## 2025-05-18 - Interactive Cards Accessibility
**Learning:** Custom clickable `<div>` elements used as cards (like `.lesson-card`) are invisible to keyboard navigation unless explicitly assigned `tabindex="0"`, `role="button"`, and keyboard event handlers (`Enter` / `Space`).
**Action:** Always complement `onclick` on non-interactive HTML elements (`<div>`, `<span>`) with `tabindex="0"`, `role="button"`, `:focus-visible` styles, and keyboard event handling.
