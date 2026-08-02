# Security policy

## Reporting a vulnerability

Email **security@clearcited.com** with a description of the issue and, if you can,
a minimal way to reproduce it. Please do not open a public issue for a security
problem.

You can expect an acknowledgement within **3 working days** and an assessment
within **10 working days**. If a fix is needed we will tell you when it ships and
credit you in the release notes unless you would rather we did not.

## Scope

These are small, dependency-free tools. Two of them run entirely in your browser
and send nothing anywhere; the Python ones use only the standard library.

In scope:

- Code execution, path traversal or injection in any of the CLIs
- A browser tool leaking input off the page
- A published PyPI artifact not matching the tagged source
- Anything in a GitHub Actions workflow that could expose a secret

Out of scope:

- Findings that depend on a modified local copy of the tool
- Missing hardening headers on the static tool pages
- Reports generated solely by an automated scanner with no demonstrated impact

## Supply chain

Python packages are published with **PyPI Trusted Publishing** (OIDC), not an API
token, and carry provenance attestations. Every release is archived on Zenodo with
a DOI, and every repository is mirrored to Codeberg with tags, so a tagged version
can always be checked against an independent copy.
