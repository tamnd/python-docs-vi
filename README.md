# Vietnamese translation of the Python documentation (auto-synced)

Vietnamese `.po` catalogs for the official Python documentation,
synchronized hourly from Transifex. Follows the process described in
[PEP 545](https://peps.python.org/pep-0545/).

**Do not hand-edit `.po` files on this repo.** The translation memory
lives on Transifex; this repo is a read-through mirror. Any commit
made directly to a version branch will be overwritten on the next sync.

Translate on Transifex: <https://app.transifex.com/python-doc/python-newest/>

## Repository layout

- `master` — GitHub Actions workflows and meta files only. No `.po`.
- `3.14` — `.po` catalogs for CPython 3.14, auto-populated by
  `.github/workflows/transifex-pull.yml`.

Additional version branches (`3.15`, …) will be added when CPython
branches the next release.

## Sibling repository

`tamnd/python-docs-vi-manual` is the hand-edited catalog built under
the PEP 545 language-switcher milestone (GLOSSARY-driven, reviewed per
file). The two repos are intentionally kept separate:

| Repo                              | Source of truth | Editable on GitHub |
|-----------------------------------|-----------------|--------------------|
| `tamnd/python-docs-vi-manual`     | This repo       | Yes (PRs)          |
| `tamnd/python-docs-vi` (this one) | Transifex       | No                 |

See [spec 0961](https://github.com/tamnd/notes) for the design.

## How to contribute Vietnamese translations

1. Create a free account at <https://app.transifex.com>.
2. Join the Vietnamese team on the
   [`python-doc/python-newest`](https://app.transifex.com/python-doc/python-newest/)
   project.
3. Translate strings there. Within a day they appear on the `3.14`
   branch of this repo.

## Documentation Contribution Agreement

> NOTE REGARDING THE LICENSE FOR TRANSLATIONS: Python's documentation is
> maintained using a global network of volunteers. By posting this project
> on Transifex, GitHub, and other public places, and inviting you to
> participate, we are proposing an agreement that you will provide your
> improvements to Python's documentation or the translation of Python's
> documentation for the PSF's use under the CC0 license (available at
> <https://creativecommons.org/publicdomain/zero/1.0/legalcode>). In
> return, you may publicly claim credit for the portion of the
> translation you contributed and, if your translation is accepted by the
> PSF, you may (but are not required to) submit a patch including an
> appropriate annotation in the `TRANSLATORS` file.

You signify acceptance of this agreement by submitting your work to the
PSF for inclusion in the documentation.
