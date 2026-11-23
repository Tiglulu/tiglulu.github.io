# tiglulu.github.io

Privacy policies and terms of use for Tiglulu's apps, served by GitHub Pages at https://tiglulu.github.io.

## The addresses never change

| Page | Address |
| --- | --- |
| Otta privacy policy | https://tiglulu.github.io/otta/privacy/ |
| Otta terms of use | https://tiglulu.github.io/otta/terms/ |

Every installed copy of the app links to these addresses, and so does the Play listing. Old app versions keep their links for years. Change the text, never the path. Do not rename this repo or the organisation, and do not move or delete these folders.

## Updating a page

The text is written in the app's own repo, as `docs/privacy-policy.md` and `docs/terms-of-service.md`, and goes through review there first. These pages are built from those files and never edited by hand.

1. Merge the text change in the app repo, with a new effective date at the top.
2. From the app repo's root: `python scripts/build_legal_pages.py <path to this repo>`
3. Check the result in a browser, then commit and push here. GitHub Pages publishes within a minute or two.

A material change to the terms or the policy may also need telling users, in the app or the release notes, before it takes effect. The documents themselves say how.

## A new app

Add a folder named after the app, with `privacy/` and `terms/` inside, and link it from `index.html`.
