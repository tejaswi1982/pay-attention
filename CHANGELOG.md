# Changelog

## 23 September 2026

Final pre-launch refinement and QA pass.

### Launch readiness

- Added canonical, Open Graph and social-card metadata to the main page.
- Added a project-specific 1200 x 630 social preview using the existing rain-street visual language.
- Added `robots.txt`, `sitemap.xml` and a restrained custom `404.html`.
- Added a concise `site-use.html` covering privacy, research limits, external services, images, attribution and corrections.
- Kept the existing Sites project and its current owner-only audience.

### Accessibility and interaction

- Removed the once-per-second live-region announcement from the attention receipt.
- Reduced receipt DOM refreshes from every second to every five seconds without changing downloaded values.
- Added focus handling when photo-recall and playground results appear.
- Added visible focus treatment for form inputs, disclosures and programmatically focused results.
- Increased disclosure and recall-label touch targets.
- Corrected the internal receipt-link arrow so it no longer implies a new window.
- Added an explicit image role to the illustrative minute allocation.

### Performance and assets

- Replaced production PNG photographs with responsive WebP derivatives at 768 px and 1536 px widths.
- Preserved the original PNG masters in `source-assets/original-png/`.
- Added lazy loading and asynchronous decoding to below-the-fold photography.
- Added high-priority loading to the first photographic experiment.
- Consolidated the three Google Font families into one stylesheet request and added connection hints.
- Reduced the production output from approximately 8.2 MiB to less than 1 MiB.

### Content and integrity

- Preserved all six findings, figures, source attributions, methodological caveats and reflection prompts.
- Preserved all exercises, scoring logic, receipt export, postcard toggles and the quiet-ending interaction.
- Replaced the remaining en dashes with words or hyphens. No em dashes or en dashes remain.
- Verified the official and publisher evidence links available to automated checking.

### Technical cleanup

- Added `noreferrer` to newly touched external links.
- Improved receipt-download reliability by attaching the generated link before activation.
- Added unique titles and descriptions for the main, site-use and 404 pages.
- Confirmed no frontend API keys, tokens, passwords, environment files or mixed-content asset requests are present.

No report statistic or factual claim was changed in this pass.
