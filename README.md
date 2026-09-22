# ISTE slide review studio

A static comparison site for the Teaching Channel Video Platform application, reviewed September 22, 2026.

## Review contents

- All 67 original slides and their proposed counterparts.
- 35 clear corrections across 28 slides, including presenter-note changes.
- Original order, most-serious-first, and highest-confidence-first rankings.
- Search, filters, text differences, enlarged slides, explanations, and high-confidence explanations.
- Original and revised PowerPoint downloads, a 66-page visible-slide PDF, and the complete change log.

This focused revision retains only clear errors, criterion/notes mismatches, out-of-scope course material, claims that conflict with their cited source, and obvious typos or formatting errors. Untested workflows, optional polishing, and speculative evidence requests are excluded. It is not a pass/fail assessment.

All 67 slides retain their original order and indicator selection. Thirty-nine slides are unchanged. Original slide 64 remains hidden and is excluded from the PDF. Course/Canvas evidence on slides 39?42 is replaced with Video Platform screenshots already present in the original deck. The interface defaults to showing only slides with fixes.

Priority reflects potential impact on the application. Confidence reflects support for a recommendation, not an ISTE passing score. Only high-confidence corrections are included. Slide priority uses the highest impact of its retained corrections. Ties use the other rating and then original slide number.

## Run locally

Open `index.html`, or run `python -m http.server 8767 --bind 127.0.0.1` from this directory. There is no build step or package installation. All resources use relative paths, including project-site deployments.

## Publish

This directory is the complete publishing artifact. Configure GitHub Pages to deploy from the `main` branch, root directory. `.nojekyll` disables Jekyll processing. See [GitHub's publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

Only the intended static site files belong in this repository. The source application, research workspace, authentication profiles, and credentials are not part of the publishing artifact.

## Verification

The local browser check exercised all 67 slide, text, and notes views; all sort modes; filters and search; hidden-slide handling; highlights and enlargement; downloads; URL state; and desktop/mobile layouts. Package checks confirmed valid relationship references, the hidden state, original file hash, and 66 visible PDF pages. The full revised deck was rendered and visually inspected.

The generated review data and build manifest in `downloads/` record slide mapping, rationale, and input/output hashes. Presenter notes are changed only to correct clear mismatches or out-of-scope references.
