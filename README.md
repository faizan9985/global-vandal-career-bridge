# Global Vandal Career Bridge

A buildless single-page student resource website. Run `python3 -m http.server 4173 --directory dist` from this folder, then open http://localhost:4173.

## Content and branding

Based on `Global Vandal Career Bridge.docx` and `Links for the website.docx` in the parent workspace. Includes nine searchable resources, four pathway filters, a browser-local five-step checklist, proposed November panel dates and campus support links.

- Official brand: https://www.uidaho.edu/brand — Pride Gold #F1B300, black #191919, silver #808080 and white. Public Sans matches the current university website typography. The official logo is preserved without alterations.
- Logo and campus photo downloaded from the university's official Content Hub via its brand page. Campus photograph description: students gathering along the Academic Mall, May 5, 2025.
- The supplied SURF URL actually leads to the Idaho AgBiz Summer Fellow Program; labeled accordingly. SURF guidance is available through the Office of Undergraduate Research link.
- Panel dates are proposed in the source plan. No registration, year, confirmed time, location or panelists have been invented.
- The requested company list was not provided, so the page directs students to Career Services for it.
- Student interviews are planned in the proposal; no placeholder videos are presented as completed work.
- Employment authorization guidance routes to IPO and USCIS. No individual eligibility advice is asserted.

Edit resources in `dist/app.js`, content in `dist/index.html`, and styles in `dist/styles.css`. External resource cards open in a new tab with accessible labels. Checklist progress stays in localStorage on the visitor's browser; no data is sent to a server. Google Fonts supplies Public Sans, with Arial as a fallback.
