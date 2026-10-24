# Palette's Journal - Critical Learnings

## 2025-05-10 - Keyboard Interactivity & Focus Outlines on Custom Interactive Cards
**Learning:** In static single-page web applications with card-based navigation (`.lesson-card`, `.q-option`), non-`button` elements used as interactive cards lack default keyboard accessibility (`tabindex="0"`, `role="button"`, and Enter/Space `onkeydown` triggers) as well as `:focus-visible` styles.
**Action:** When adding keyboard navigation to card elements, ensure both `tabindex="0"`, `role="button"`, and `onkeydown="if(event.key==='Enter'||event.key===' '){event.preventDefault(); ...}"` are added alongside custom `:focus-visible` outline styles so keyboard users get standard focus and activation feedback.
