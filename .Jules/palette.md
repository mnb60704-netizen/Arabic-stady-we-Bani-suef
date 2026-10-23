## 2025-05-18 - Keyboard Navigation for Static Interactive Cards
**Learning:** In static HTML single-page apps using `div` elements with `onclick` handlers for key interactive components (cards, quiz options), full keyboard accessibility requires `tabindex="0"`, `role="button"`, explicit `:focus-visible` ring/outline styles, and `Enter`/`Space` keydown event handlers.
**Action:** Always check interactive cards and option buttons for `tabindex`, `role="button"`, focus indicators, and keydown listeners when working on pure HTML/JS study or quiz interfaces.
