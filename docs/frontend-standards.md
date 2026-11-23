# Frontend standards

## File organization

| Path | Purpose |
| --- | --- |
| Root `.html` files | Main-site pages. Use one file per page. |
| `assets/css/` | Shared styles and page-specific styles where needed. |
| `assets/js/` | Browser interactions and shared recommendation logic. |
| `assets/js/data/` | Shared curated destination data. |
| `assets/images/` | Optimized images used by the site. |
| `assets/vendor/` | Third-party browser libraries if bundled locally. |
| `react-demo/` | Separate React recreation of one main-site page. |

Create folders as files need them. Use lowercase kebab-case filenames, descriptive identifiers, and relative asset links. Keep styles and scripts in their own files. Run the main site with a local static server for browser testing.

## Implementation

- Use semantic HTML and a logical heading order. Give every page a descriptive title and meta description. Use links for navigation, buttons for actions, associated labels for form fields, and appropriate alt text for images.
- Build mobile-first. Use Grid for card layouts and Flexbox for navigation and control groups. Share colors and spacing through CSS custom properties. Provide clear hover and keyboard focus states.
- Keep the destination dataset shared across pages. Separate filtering and recommendation scoring from rendering. Register event handlers in JavaScript. Render plain-text values with `textContent`.
- Use at least one JavaScript library for a visible interaction in the main site. Keep the rest of the main-site logic readable in plain JavaScript.

## Verification

Check affected pages at mobile, tablet, and desktop widths. For interactive changes, exercise keyboard navigation and relevant success, error, and empty states. Check links and browser console errors. The final project needs testing in at least two browsers.
