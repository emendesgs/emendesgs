## 2026-05-04 - Accessibility of Social Badges
**Learning:** Social links containing badge images are inaccessible when the anchor tags use an invalid `alt` attribute and the inner `<img>` tags lack an `alt` attribute. Screen readers cannot properly identify the link's purpose.
**Action:** Always use `aria-label` on icon-only anchor tags and proper `alt` attributes on decorative or informative images within links to ensure screen readers provide correct context.
