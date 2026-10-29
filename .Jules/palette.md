## 2025-05-18 - Lesson Cards Keyboard Accessibility Pattern
**Learning:** In static HTML applications like `arabic_study.html`, card components (`.lesson-card`) rendered as `<div>` with `onclick` lack built-in keyboard accessibility and focus indicators.
**Action:** Always pair `role="button"`, `tabindex="0"`, and `onkeydown` handlers with `:focus-visible` ring CSS for custom interactive container elements.
