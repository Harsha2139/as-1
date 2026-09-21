# Second-pass repair report

Student: T. Harshavardhan Reddy
Section: 6
PRN: 250200448

## Repairs
- Repaired HTML-012 so it demonstrates actual CSS selectors plus colors, fonts, margins, padding and borders.
- Repaired HTML-014 to use a bundled local Bootstrap stylesheet and real Bootstrap components, so it works offline.
- Repaired duplicated/generic JavaScript demonstrations in core, DOM, events, forms and browser sections, including functions vs arrow functions, objects vs classes, API fetch vs dynamic API display, regex vs email validation, class add/remove vs toggle, distinct mouse/keyboard/event propagation demos, typing test, login/signup/feedback/admission forms, URL/language/history/online-offline browser tasks, and geolocation tasks.
- Added local Bootstrap 3.4.1 CSS under `assets/bootstrap.min.css`.

## Static verification
- 566 HTML files present (555 numbered program pages + 11 hubs/index/report pages).
- 270 CSS numbered pages; 270 JavaScript numbered pages.
- JavaScript inline scripts and event-handler snippets: syntax-checked with Node.js; no syntax errors.
- CSS blocks and shared stylesheet: parsed with tinycss2; no CSS parse errors.
- Local media/resources: checked; no missing local `src` resources.
- Local hyperlinks/resources: previously audited at 0 broken local links/resources.
- Duplicate HTML IDs: previously audited at 0.

## Note
The two API demonstrations still depend on network access for live data, but both have safe offline fallback behavior. Browser geolocation/history controls depend on browser permissions/history as expected.
