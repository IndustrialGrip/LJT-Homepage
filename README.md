# Junteng Liu — LJT-Homepage

A single-page academic homepage forked from [Academic Pages](https://github.com/academicpages/academicpages.github.io).

## Content

The existing [`_pages/about.md`](_pages/about.md) contains the biography, research interests, education, research internships, all six publications with the author lists and venues supplied in memory, the Zhiyuan Honor Scholarship, and contact information.

All personal and academic content is limited to the supplied memory. Dates and the stored first-year PhD description are preserved. No photograph, separate skills list, paper URLs, or internship project descriptions were supplied, so none are inferred. Named code repositories are mentioned without guessing their URLs.

The site's GitHub profile link remains **Vicent0205**, as recorded in memory. **IndustrialGrip** is the account hosting this fork, not a replacement for that personal contact link.

## Single-page structure

- `_pages/about.md`: the only published HTML content page, at `/`.
- `_data/navigation.yml`: links to sections of that same page, including `/#publications`.
- `_config.yml`: profile metadata, the `/LJT-Homepage` project base path, and exclusions for all template example pages and collections.
- `_includes/author-profile.html`: sidebar with only the supplied identity and contact details; no placeholder portrait.

Upstream demonstration files remain in the fork as source but are excluded from the built site. No additional content pages or publication detail pages have been created.

## Enable GitHub Pages

The site is configured for **https://industrialgrip.github.io/LJT-Homepage/**.

To publish it, open [Settings → Pages](https://github.com/IndustrialGrip/LJT-Homepage/settings/pages), select **Deploy from a branch**, choose **master** and **/ (root)**, and save. The address is not live until GitHub Pages is enabled and its deployment succeeds.

## Build and validation

The `Jekyll build` workflow checks the site on pushes to `master`, pull requests, and manual runs. It builds with strict front matter and verifies that only `index.html` is generated, all six publications and the expected sections are present, no profile placeholders remain, and project-relative asset and navigation links resolve. The workflow uploads the generated site as an artifact; it does not enable GitHub Pages.

If GitHub Actions is disabled for the fork, enable it in the repository's Actions tab before running this check.

To build locally:

```sh
bundle install
bundle exec jekyll build --strict_front_matter
bundle exec jekyll serve
```

The local preview is at `http://localhost:4000/LJT-Homepage/`.

The Academic Pages theme and its MIT license are retained.
