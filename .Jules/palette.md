## 2025-05-18 - Arabic Study App Keyboard Accessibility & Quiz Buttons
**Learning:** Dynamic quiz options rendered as `<div>` elements and non-semantic `.lesson-card` containers prevent screen readers and keyboard-only users from focusing and activating core navigation and quiz flows.
**Action:** Always render interactive options using semantic `<button type="button">` or add explicit `role="button"`, `tabindex="0"`, `onkeydown` listeners, and `:focus-visible` styling for interactive card elements.
