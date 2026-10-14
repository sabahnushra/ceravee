# Sabah Nushra — Academic Website

Static, GitHub Pages-compatible academic homepage. Upload the **contents of this directory** to the root of `sabahnushra.github.io`.

## Updating publication links

Open `index.html`, find `Publications & manuscripts`, and look for each paper’s `pub-links` block:

```html
<div class="pub-links">
  <a href="papers/example.pdf" target="_blank" rel="noopener noreferrer">Paper ↗</a>
  <a href="" target="_blank" rel="noopener noreferrer">Code ↗</a>
  <a href="" target="_blank" rel="noopener noreferrer">Project page ↗</a>
</div>
```

The empty links are **automatically hidden** by CSS. To activate a Code or Project page link, just paste the URL between its `href` quotes. No other edits are needed. The same technique is used for the Bangla disease-prediction paper's link because a matching current public PDF was not available.

The BILAL-BENCH paper links to its OpenReview PDF, and the uploaded CRuSS and Medical VQA drafts are bundled under `papers/`.

**Important:** Publishing draft PDFs on a personal website may compromise anonymous conference review. Check applicable venue policies before pushing under-review PDFs to a public repository. If necessary, leave their Paper `href` empty until public sharing is appropriate.

## Files

- `index.html` — content and publication links
- `style.css` — styling and mobile layout
- `images/sabah-portrait.webp` — portrait
- `papers/` — local PDF downloads
- `Sabah_Nushra_CV.pdf` — academic CV
