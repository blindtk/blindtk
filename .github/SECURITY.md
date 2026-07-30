# Security Policy

This repository is Daniel Malaco's GitHub profile: a `README.md`, five
SVGs generated into `assets/`, and four workflows
(`.github/workflows/update-profile-widgets.yml`,
`.github/workflows/lint-actions.yml`, `.github/workflows/gitleaks.yml`,
`.github/workflows/scorecard.yml`) that keep it updated and audited. There
is no application or user data here — the relevant surface is the CI/CD
chain itself: `update-profile-widgets.yml` runs with `permissions:
contents: write` in the job that commits, and its `generate` job runs
third-party code (the stats action, the trophy generator) before that.

## How to report a vulnerability

Report **privately**, never in a public Issue (an Issue exposes the flaw
to everyone before it's fixed):

- Through the contact page: <https://danielmala.co/contactos/>

Also see the site's `security.txt`
([`/.well-known/security.txt`](https://danielmala.co/.well-known/security.txt)),
in [RFC 9116](https://www.rfc-editor.org/rfc/rfc9116) format.

Include, if possible: what you found, steps to reproduce, and the impact
you'd assign it.

## What to expect

- Response typically within **24–48h, on business days**.
- We ask for coordinated disclosure: give time to fix before going public.

## Out of scope

Automated scanner reports with no demonstrable impact (e.g., a missing
action pin that's already been fixed, a third-party badge that's
offline). See [`blindtk/personal-site`](https://github.com/blindtk/personal-site)
for the full security policy covering the site and the Worker.
