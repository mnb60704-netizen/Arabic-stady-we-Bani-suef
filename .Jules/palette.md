# Palette UX Journal

## 2026-10-27 - Interactive Card Accessibility in Static Single-Page Apps
**Learning:** Custom clickable `<div>` cards without proper ARIA semantics (`role="button"`, `tabindex="0"`) or keyboard handlers (`Enter` / `Space`) are invisible to screen readers and unreachable by keyboard-only users.
**Action:** Always complement `onclick` handlers on non-interactive elements with `role="button"`, `tabindex="0"`, explicit `aria-label`, keydown event listener, and CSS `:focus-visible` outline.
