# TODO - DeTech FireLink update

## Goal
Integrate the provided raw `index.html` (with popup + gated site) into the Next.js app under `firelink/`.

## Steps
- [ ] Create `firelink/public/images/` and copy existing `images/*` assets so the page can load them via `/images/...`.
- [ ] Replace `firelink/app/page.tsx` with a client component version of the provided HTML (popup + main site) so Firebase/form logic runs.
- [ ] Ensure any Next.js/React quirks are handled (no duplicate `<html>/<body>`, correct JS execution in client side).
- [ ] Start dev server and verify the popup + localStorage gating works.
- [ ] Fix any runtime/build errors that appear.

