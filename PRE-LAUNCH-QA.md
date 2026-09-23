# PAY ATTENTION. Pre-launch QA

Audit date: 23 September 2026

## Outcome

The site is deployed as an owner-private production version. The central idea, editorial structure, six controlled visual interventions, factual report content and major interaction model have been preserved.

## Passed checks

### Identity and anti-template audit

- The rendered design remains warm paper, black type, black-and-white photography, restrained cobalt and vermilion, with acid lime used once as a signal strip.
- No SaaS feature grid, pricing structure, testimonials, dashboard fiction, liquid glass, glowing orbs, generic pastel system, icon library or decorative emoji system was introduced.
- Existing shadows, rotations and photographic overlays remain limited to conceptually useful moments.
- Motion remains optional, brief and user-initiated. There is no autoplay, infinite feed, notification prompt or manipulative scroll effect.
- The page still has a clear editorial composition underneath each rebellious intervention.

### Content and research integrity

- Six report findings remain present.
- Report numbers, dates, populations, source notes, limitations, evidence disclosures and reflection prompts were not changed.
- The report still states that it is desk research, not an original representative survey or attention-span assessment.
- AI-generated scenes remain clearly labelled as fictional illustrations.
- PIB, Ormax, Microsoft, DataReportal, PsyToolkit Stroop and PsyToolkit SART links resolved during the audit.
- The LinkedIn profile URL is well formed. Automated retrieval was blocked by LinkedIn, so its final availability should be spot-checked in a normal signed-out browser.
- Global text search found no em dash or en dash characters.

### Accessibility

- One page-level `h1` is present on each HTML page and heading order is coherent.
- Skip links, landmarks, labelled navigation, labels, fieldsets, legends, tab roles and button semantics are retained.
- All meaningful images have concise alt text. The duplicate visual cutout has empty alt text and is hidden from assistive technology.
- Focus indicators cover links, buttons, select controls, radio inputs, disclosures and dynamic results.
- Keyboard interaction remains available for exercise tabs, colour answers and the exception exercise.
- Dynamic results receive focus once. The receipt no longer announces a changing timer every second.
- Reduced-motion CSS disables smooth scrolling and visual transitions. Essential content does not depend on motion.
- Core text colour pairs meet WCAG AA contrast. The vermilion hero word is large display text and exceeds the large-text threshold.
- Interactive targets are at least 44 px where the custom styling controls their size.

### Responsive behaviour

- CSS includes intentional layouts for desktop, tablet, common phones and a dedicated 380 px breakpoint.
- The 320 px case changes the exchange diagram to one column and the exercise tabs to a vertical control.
- Responsive images supply 768 px and 1536 px choices.
- Fixed widths are bounded by max-width rules and receipt text can wrap.
- No source-level cause of horizontal overflow was found.

### Performance

- Production output is approximately 0.93 MiB.
- The three original production PNGs totalling approximately 8.2 MiB were replaced by responsive WebP derivatives.
- Original PNG masters remain in the repository outside `dist`.
- Below-the-fold photographs use lazy loading and asynchronous decoding.
- The first photograph uses a high fetch priority and keeps explicit dimensions to limit layout shift.
- JavaScript is approximately 14 KiB and has no framework or third-party runtime dependency.
- CSS is approximately 34 KiB across the existing base and editorial refinement files.
- No video, audio, analytics or advertising script is loaded.

### Security and privacy

- No `.env` file is present.
- No frontend API key, password, bearer token or private credential was found.
- No external `http://` asset or script request is present. The only `http://` strings are the sitemap XML namespace and an encoded inline SVG namespace.
- Production and canonical URLs use HTTPS.
- The site has no account, contact form, user submission, database or persistent browser storage.
- No analytics or non-essential cookie is configured, so no cookie banner was added.
- The privacy and site-use page documents page-memory exercise data, local receipt creation, hosting requests, Google Fonts and external links.

### Metadata and crawling

- Main title and description are project-specific.
- Canonical, Open Graph and Twitter card metadata are present.
- The social preview is 1200 x 630 and uses the project photography and editorial palette.
- The existing exclamation-mark favicon is preserved and colour-aligned with the current palette.
- `robots.txt`, `sitemap.xml` and a project-specific `404.html` are present.
- The 404 page is marked `noindex,follow`.

### Functional and source checks

- `app.js` passes Node syntax checking.
- Three HTML pages pass local-file, anchor, duplicate-ID, image-alt, title, description and blank-target security checks.
- All source image paths resolve to files in `dist`.
- The main navigation, report anchor, playground anchor, receipt anchor and footer utility link resolve locally.
- Source links use HTTPS and open separately with `noopener` protection.
- The production home page and site-use page returned HTTP 200 after deployment.
- Production `robots.txt`, `sitemap.xml`, the social preview and the 768 px responsive street image returned HTTP 200.
- An unknown production path returned HTTP 404 with the custom project page.
- The production service screenshot shows the intended desktop hero, loaded typefaces, correct palette, clean hierarchy and updated receipt arrow.
- Optimized photographic files were visually inspected after conversion. No damaging compression artefacts were found.

### Browser regression basis

- The most recent full interaction suite, completed 18 September 2026, covered desktop, 305 px, 375 px and 753 px content widths, all three exercises, photo recall, postcard toggles, report disclosures, keyboard tabs, receipt updates, PNG export and the quiet-ending timer.
- This pass did not alter exercise scoring, timers, source data or the major interaction model. The JavaScript changes were limited to result focus, receipt refresh frequency and a more reliable download-link activation.
- The final production shell was visually verified from the hosting service screenshot. The owner-private sign-in gate prevented an identity-less cloud browser from repeating the full viewport suite without an interactive account sign-in. The site audience was not changed to work around that boundary.

## Not applicable

- Form submission validation: there is no submitted public form. The photo-recall exercise uses native required radio validation and never sends data.
- Spam protection and CAPTCHA: there is no public submission endpoint.
- Cookie consent: there are no non-essential cookies or tracking scripts.
- Analytics credentials: analytics were deliberately not added.
- Ecommerce terms, pricing, payments and refunds: no commercial transaction exists.
- Loading skeletons: there is no genuine asynchronous data interface.
- Civic or political neutrality checks for elected representatives: the project contains no MP, party, constituency or election data.
- Backend secrets and runtime environment variables: the site is static and requires none.

## Remaining external actions

1. The ChatGPT Site remains owner-private. Change the audience to public only when you are ready for public launch.
2. If a custom domain is connected, configure its DNS and then update the canonical URL, `og:url`, social-image URL and sitemap locations to that final hostname.
3. Open the LinkedIn credit once in a normal signed-out browser because LinkedIn blocked automated retrieval during this audit.
4. Run a brief physical-device spot check on at least one iPhone and one Android device before a promoted launch. Automated viewport checks cannot reproduce every mobile font and browser behaviour.
5. If analytics are added later, choose a privacy-conscious service, document the fields collected and reassess consent requirements before enabling it.

No Railway, email service, database or API configuration is required for this static microsite.
