# PAY ATTENTION · website files

This is a static website: HTML + CSS + JavaScript + images. No Python, npm install, database, payment service or runtime AI API is required.

## Files

- `dist/index.html`: all page content, report findings, citations and page structure.
- `dist/style.css`: colours, typography, layouts, responsive styles and transitions.
- `dist/encore.css`: editorial refinement, six controlled interventions and responsive overrides.
- `dist/app.js`: exercises, scoring, postcard text toggles, receipt download and quiet moment.
- `dist/assets/`: responsive WebP scenes and the project-specific social preview used by the production site.
- `source-assets/original-png/`: preserved original AI-generated PNG masters, excluded from production output.
- `dist/site-use.html`: concise privacy, research and site-use information.
- `dist/404.html`, `dist/robots.txt`, `dist/sitemap.xml`: launch and crawl support.
- `CHANGELOG.md`: final refinement record.
- `PRE-LAUNCH-QA.md`: audit results, non-applicable checks and external launch actions.
- `.openai/hosting.json`: identity and static-output settings for the existing ChatGPT Site. Do not copy this identity into a newly created Site.

The contents of `dist/` are the current production output. Its HTML, CSS, JavaScript and assets are ready for a static web host.

## View on your own computer

1. Open the `dist` folder.
2. Double-click `index.html`, or serve `dist` with a local static server.
3. Keep the utility pages, CSS, JavaScript and `assets/` beside it. Internet access loads Google Fonts and external source links; system fonts are the fallback.

## Edit

Open the extracted folder in VS Code. Edit content in `index.html`, visual styling in `encore.css` (with base components in `style.css`), and behaviours in `app.js`. Save and refresh your browser. Changes on your computer do not update the hosted site automatically.

## Publish using the existing ChatGPT Site

The site is already hosted at https://pay-attention-exhibition.abhinandan-tejaswi.chatgpt.site . The present publication remains access-limited until you change who can visit.

Open Sites in ChatGPT, find PAY ATTENTION, select Share, and choose “Anyone on the internet” when you are ready for a public audience. The account currently offers a public access option. Confirm/save the sharing choice if prompted, then test the URL while signed out or in a private browser window. You can also explicitly ask ChatGPT to make this Site public.

Official walkthrough: https://learn.chatgpt.com/training/walkthroughs/building-a-shareable-site

## Publish elsewhere

Any host that serves static files can serve this site. Upload the contents of `dist` so `index.html` is at the published root, keeping relative paths intact. There is no build command. Access limits in ChatGPT do not transfer to an external host; configure its visibility separately. A custom domain is optional and requires ownership plus the host’s DNS instructions.

## Content and data notes

Edition 01 of The Indian Attention Report is a desk-researched synthesis, not a new representative survey. The source/date, population and limitation for each finding are in the page. Report reflection questions collect no responses. Exercise results are held in the page’s memory and disappear on reload. The website has no configured tracking analytics. Hosting infrastructure and Google Fonts may process ordinary web requests.

The images are generated illustrative scenes, not participant photographs. Public source links do not transfer ownership of the underlying reports.

## Verification

JavaScript syntax, local asset references, unique IDs, report count and navigation targets were checked. The final launch audit and production endpoint checks are documented in `PRE-LAUNCH-QA.md`. The full browser suite completed on 18 September 2026 covered desktop, phone and tablet layouts, all three exercises, photo recall, postcard toggles, report disclosures, keyboard tab navigation, receipt updates, actual PNG export and the quiet-ending timer. These are browser layout checks, not physical-device tests.


## Editorial refinement: 18 September 2026

Warm paper, clean Barlow Condensed headlines, readable DM Sans and restrained blue/vermilion accents. Six controlled interventions are documented in DESIGN-NOTES.md. Report findings, source links, methodological caveats and the three original photographic compositions are preserved.

An optional Vite development preview is included in the source repository for browser testing (`npm install`, then `npm run dev`). It is not required for hosting. The `dist` folder is the production output.
