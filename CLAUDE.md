# Anniversary Alley — notes for anyone editing this site

- **Every page must include the Meta (Facebook) Pixel**, ID `395674804265892`, inside `<head>`.
  Netlify deploys straight from this repo, so if the pixel isn't in these files it disappears from the live site.
  When adding a new page, copy the pixel block from `index.html`.
- Pixel events in use: `Lead` on both forms on index.html (`#signupForm` reminder sign-up and `#contactForm` planning form — the original conversion setup),
  plus `SubmitApplication` (planning profile on plan.html).
  Ads may optimize on these, so don't rename them.
- Free-spots badge: update `FREE_SPOTS_LEFT` in both `index.html` and `plan.html`.
