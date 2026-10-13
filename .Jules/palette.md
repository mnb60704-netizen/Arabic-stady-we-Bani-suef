## 2025-05-18 - Lesson Cards Keyboard Accessibility in Arabic Study App
**Learning:** Interactive `<div>` elements used as cards require `role="button"`, `tabindex="0"`, `:focus-visible` styling, and keydown listeners (Enter / Space) to be fully accessible for keyboard and screen reader users in static HTML apps.
**Action:** Always complement `onclick` on non-interactive HTML tags with `role="button"`, `tabindex="0"`, `:focus-visible`, and `onkeydown="if(event.key==='Enter'||event.key===' ') ..."` or unified handler.
