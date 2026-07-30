<img src="./assets/banner.svg" alt="Banner: Daniel Malaco, Information Security Engineer, Porto, Portugal" />

Information Security Engineer designing and operating the security
architecture for critical infrastructure. Came up through networks before
moving into security.

## What I do

- Design, deploy and operate the security architecture for critical
  infrastructure: NGFW, AV/EDR, vulnerability analysis, SIEM, IAM, WAF,
  secure email gateway.
- Run the full detection cycle end to end — from designing the control to
  analyzing the event and closing the incident through ITSM.
- Bring an offensive perspective into defensive work — thinking like an
  attacker shapes how I design and tune detections.
- Build for redundancy, document for whoever comes next, test in staging
  before touching production — habits from infrastructure where a network
  failure is not an inconvenience, it's a stopped system.

## Stack

**Security**

![NGFW](https://img.shields.io/badge/NGFW-EE1F25?style=flat-square&logo=fortinet&logoColor=white&labelColor=0a0d11)
![WAF](https://img.shields.io/badge/WAF-4aa8ff?style=flat-square&labelColor=0a0d11)
![Security Email Gateway](https://img.shields.io/badge/Security%20Email%20Gateway-3ddc84?style=flat-square&labelColor=0a0d11)
![AV](https://img.shields.io/badge/AV-f5b544?style=flat-square&labelColor=0a0d11)
![EDR](https://img.shields.io/badge/EDR-4aa8ff?style=flat-square&labelColor=0a0d11)
![IAM](https://img.shields.io/badge/IAM-3ddc84?style=flat-square&labelColor=0a0d11)
![Active Directory](https://img.shields.io/badge/Active%20Directory-f5b544?style=flat-square&labelColor=0a0d11)
![SIEM](https://img.shields.io/badge/SIEM-4aa8ff?style=flat-square&labelColor=0a0d11)
![Vulnerability Assessment](https://img.shields.io/badge/Vulnerability%20Assessment-3ddc84?style=flat-square&labelColor=0a0d11)
![Penetration Testing](https://img.shields.io/badge/Penetration%20Testing-f5b544?style=flat-square&labelColor=0a0d11)
![Business Continuity Planning](https://img.shields.io/badge/Business%20Continuity%20Planning-4aa8ff?style=flat-square&labelColor=0a0d11)

**Platforms**

![Linux](https://img.shields.io/badge/Linux-f5b544?style=flat-square&logo=linux&logoColor=white&labelColor=0a0d11)
![Windows](https://img.shields.io/badge/Windows-4aa8ff?style=flat-square&logo=windows&logoColor=white&labelColor=0a0d11)
![AWS](https://img.shields.io/badge/AWS-3ddc84?style=flat-square&logo=amazonaws&logoColor=white&labelColor=0a0d11)
![Azure](https://img.shields.io/badge/Azure-4aa8ff?style=flat-square&logo=microsoftazure&logoColor=white&labelColor=0a0d11)
![Rapid7 InsightVM](https://img.shields.io/badge/Rapid7%20InsightVM-f5b544?style=flat-square&labelColor=0a0d11)
![ServiceNow](https://img.shields.io/badge/ServiceNow-3ddc84?style=flat-square&logo=servicenow&logoColor=white&labelColor=0a0d11)

**Languages**

![Python](https://img.shields.io/badge/Python-3ddc84?style=flat-square&logo=python&logoColor=white&labelColor=0a0d11)
![Bash](https://img.shields.io/badge/Bash-f5b544?style=flat-square&logo=gnubash&logoColor=white&labelColor=0a0d11)
![PowerShell](https://img.shields.io/badge/PowerShell-4aa8ff?style=flat-square&logo=powershell&logoColor=white&labelColor=0a0d11)
![Go](https://img.shields.io/badge/Go-3ddc84?style=flat-square&logo=go&logoColor=white&labelColor=0a0d11)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-f5b544?style=flat-square&logo=cplusplus&logoColor=white&labelColor=0a0d11)

**Frameworks**

![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-3ddc84?style=flat-square&labelColor=0a0d11)
![CIS Benchmarks & Controls](https://img.shields.io/badge/CIS%20Benchmarks%20%26%20Controls-4aa8ff?style=flat-square&labelColor=0a0d11)
![CISA CPG](https://img.shields.io/badge/CISA%20CPG-f5b544?style=flat-square&labelColor=0a0d11)
![OWASP Top 10](https://img.shields.io/badge/OWASP%20Top%2010-3ddc84?style=flat-square&logo=owasp&logoColor=white&labelColor=0a0d11)
![ISO 27001](https://img.shields.io/badge/ISO%2027001-4aa8ff?style=flat-square&labelColor=0a0d11)
![NIS2](https://img.shields.io/badge/NIS2-f5b544?style=flat-square&labelColor=0a0d11)
![OpenSSF Scorecard](https://img.shields.io/badge/OpenSSF%20Scorecard-3ddc84?style=flat-square&labelColor=0a0d11)

## Projects

**[danielmala.co](https://github.com/blindtk/personal-site)** is the project I keep public, and it's built the way I think infrastructure should be: least privilege by default, with every exception argued for instead of left implicit.

That shows up everywhere in it — a strict Content-Security-Policy with no
`'unsafe-inline'` clause, zero client-side JavaScript unless a feature
genuinely needs it, and tools that call home (a compromised-password
check via k-anonymity, a header self-scan) labeled as such instead of
pretending to run entirely in the browser. The one piece that does need
a server — a honeypot logging automated scanning against decoy
endpoints — lives isolated in a Cloudflare Worker, and can't store an IP
even if I wanted it to: only country, ASN, and path, keyed by a
rotating salted hash. None of this is asserted on faith — the site's
*Evidence* page deep-links the commits, workflows, and a live header
scan behind each claim.

## Statistics

<div align="center">

<img src="./assets/github-stats.svg" alt="Daniel Malaco's GitHub stats" width="49%" />
<img src="./assets/top-langs.svg" alt="Daniel Malaco's most-used languages on GitHub" width="49%" />

<img src="https://streak-stats.demolab.com/?user=blindtk&hide_border=true&background=0a0d11&border=161c28&stroke=161c28&ring=3ddc84&fire=f5b544&currStreakLabel=3ddc84&currStreakNum=e6edf3&sideNums=e6edf3&dates=8593a5&sideLabels=8593a5" alt="Daniel Malaco's GitHub contribution streak" />

<img src="./assets/trophies.svg" alt="Daniel Malaco's GitHub profile trophies" />

<img src="./assets/stars-given.svg" alt="Number of repositories Daniel Malaco has starred on GitHub" />

</div>

Banner, stats, top languages, trophies and the starred-repos count are
generated weekly by
[`.github/workflows/update-profile-widgets.yml`](.github/workflows/update-profile-widgets.yml)
and committed to `assets/` — no live third-party endpoint is queried when
someone loads this profile. The streak card still calls
`streak-stats.demolab.com` directly, which is up and stayed out of scope
for self-hosting.

[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/blindtk/blindtk/badge)](https://securityscorecards.dev/viewer/?uri=github.com/blindtk/blindtk)

This repo's own CI/CD is scored by
[OpenSSF Scorecard](.github/workflows/scorecard.yml) — pinned actions,
minimal per-job permissions, branch protection with required review — the
same controls this profile talks about, applied to the workflow that
maintains it.

A few checks stay low on purpose, not by oversight: `Contributors` and
`Fuzzing` don't fit a single-maintainer profile repo with no application
code to fuzz, and `CII-Best-Practices` targets a governance questionnaire
built for software projects, not a GitHub profile. Faking any of those to
move the number would be the opposite of what this page is meant to show.

Public activity here is a fraction of the work — most of it is internal
infrastructure, not public code.

## Contact

[![Website](https://img.shields.io/badge/Website-danielmala.co-3ddc84?style=flat-square&labelColor=0a0d11)](https://danielmala.co)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-danielmalaco-4aa8ff?style=flat-square&logo=linkedin&logoColor=white&labelColor=0a0d11)](https://www.linkedin.com/in/danielmalaco)
[![Email](https://img.shields.io/badge/Email-me%40danielmala.co-f5b544?style=flat-square&logo=maildotru&logoColor=white&labelColor=0a0d11)](mailto:me@danielmala.co)
[![Credly](https://img.shields.io/badge/Credly-badges-3ddc84?style=flat-square&labelColor=0a0d11)](https://www.credly.com/users/daniel-malaco/badges)

<div align="right">

<img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fblindtk&countColor=%233ddc84&style=flat-square&labelColor=%230a0d11" alt="Visitor count badge for this GitHub profile" />

</div>
