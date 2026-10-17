## 2025-05-18 - Keyboard Navigation & Focus Visible for Custom Interactive Elements
**Learning:** Custom interactive elements (such as `div.lesson-card` or `div.q-option` with `onclick`) in static HTML apps are invisible to keyboard-only users unless explicitly assigned `tabindex="0"`, `role="button"`, `:focus-visible` styles, and keyboard activation (`Enter`/`Space`) event handlers.
**Action:** Always verify custom clickable `div`s have proper keyboard focus support and key listeners for accessible navigation.
