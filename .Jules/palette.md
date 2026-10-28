## 2025-05-18 - Keyboard Navigation & Screen Reader Support
**Learning:** Interactive `<div>` elements used as cards or quiz choices in static HTML apps lack native keyboard focus and ARIA accessibility unless explicitly assigned `role="button"`, `tabindex="0"`, descriptive `aria-label`s with titles, and keyboard event listeners (`Enter`/`Space`).
**Action:** Always provide explicit lesson/item title names in `aria-label` attributes on cards so screen readers don't announce identical non-descriptive labels across interactive elements.
