# Contributing

Thanks for looking. These are deliberately small tools, and that is the main thing
to know before opening a pull request.

## The constraints

- **Zero dependencies.** The Python tools use the standard library only; the
  browser tools are one HTML file and one JS file with no build step. A pull
  request that adds a dependency will almost certainly be declined — please open
  an issue first and make the case.
- **Python 3.9+.**
- **Mock mode keeps working offline.** Anything that needs a network call or an
  API key must degrade to the built-in mock path.
- **No claim without a source.** These tools report *observed correlations*, not
  guarantees. If a change adds or edits user-facing wording that asserts how an AI
  engine behaves, say in the pull request where that came from.

## Good first contributions

Bug reports with a reproduction, a failing input we mis-handle, a signal we detect
badly, documentation that is wrong or out of date, or a JSON-LD template for a type
that matters and is missing.

## Pull requests

1. Keep it focused — one change per pull request.
2. Say what you ran to check it. There is no test suite yet; running the tool
   before and after on a real input is the bar.
3. Match the surrounding style. No reformatting passes mixed into a behaviour change.

Commit messages should say what changed **and why** — the why is the part that is
useful a year later.

## Releases and citation

Every release is tagged, published to PyPI via Trusted Publishing, archived on
Zenodo with a DOI, and mirrored to Codeberg with tags. If you contribute something
substantial and would like to be listed in `CITATION.cff`, just say so.

## Reporting something sensitive

See [SECURITY.md](SECURITY.md). Do not open a public issue for a security problem.
