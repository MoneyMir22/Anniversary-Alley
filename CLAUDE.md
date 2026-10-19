# Anniversary Alley — notes for anyone editing this site

- **Every page must include the Meta (Facebook) Pixel**, ID `395674804265892`, inside `<head>`.
  Netlify deploys straight from this repo, so if the pixel isn't in these files it disappears from the live site.
  When adding a new page, copy the pixel block from `index.html`.
- Pixel events in use: `Lead` (reminder sign-up form `#signupForm` on index.html — the original conversion event),
  `Contact` (short planning form), `SubmitApplication` (planning profile on plan.html).
  Ads may optimize on these, so don't rename them.
- Free-spots badge: update `FREE_SPOTS_LEFT` in both `index.html` and `plan.html`.
