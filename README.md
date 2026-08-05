<img src="./assets/banner.svg" alt="Banner: Daniel Malaco, Information Security Engineer, Porto, Portugal" />

Information Security Engineer designing and operating the security
architecture for critical infrastructure. Came up through networks before
moving into security. Most of the work is private — what's here
demonstrates the practices behind it.

## Highlights

- Security architecture for NIS2-regulated critical road infrastructure, on-premises and in the cloud
- Full detection-to-response cycle — control design, detection engineering, investigation, incident response — backed by SANS SEC504 (Incident Handling)
- IP network delivered across 4 countries: Qatar, Brazil, Denmark, Norway
- Security infrastructure work featured in a [Fortinet Customer Story](https://www.fortinet.com/customers/ascendi)
- DevSecOps practice on public projects — zero-trust CI/CD, supply-chain security, and an edge-computing (Cloudflare Workers) backend — [danielmala.co](https://danielmala.co)
- Frameworks applied day to day, not just referenced: MITRE ATT&CK, CIS Controls, OWASP Top 10

## What I do

- Design, deploy and operate security architecture across on-prem and
  cloud infrastructure: NGFW, AV/EDR, VA, SIEM, IAM, WAF, SEG.
- Run the full detection cycle end to end — control design, detection
  engineering, incident investigation and response, closing out through
  ITSM.
- Apply security frameworks (MITRE ATT&CK, CIS Controls, ISO 27001, OWASP
  Top 10) to structure decisions and prioritize controls, not just to
  reference them.
- Bring an offensive perspective into defensive work — thinking like an
  attacker shapes how I design and tune detections.
- Build for redundancy, document for whoever comes next, test in staging
  before touching production — habits from infrastructure where a network
  failure is not an inconvenience, it's a stopped system.

## Stack

**Security**

_Network_

![Fortinet](https://img.shields.io/badge/Fortinet-B91C1C?style=flat-square&logo=fortinet&logoColor=white&labelColor=0a0d11)
![Palo Alto Networks](https://img.shields.io/badge/Palo%20Alto%20Networks-2563eb?style=flat-square&logo=paloaltonetworks&logoColor=white&labelColor=0a0d11)
![Cloudflare](https://img.shields.io/badge/Cloudflare-15803d?style=flat-square&logo=cloudflare&logoColor=white&labelColor=0a0d11)

_Endpoint & detection_

![AV](https://img.shields.io/badge/AV-2563eb?style=flat-square&labelColor=0a0d11)
![EDR](https://img.shields.io/badge/EDR-15803d?style=flat-square&labelColor=0a0d11)
![Splunk](https://img.shields.io/badge/Splunk-b45309?style=flat-square&logo=splunk&logoColor=white&labelColor=0a0d11)
![Elastic](https://img.shields.io/badge/Elastic-2563eb?style=flat-square&logo=elastic&logoColor=white&labelColor=0a0d11)

_Identity & access_

![Entra ID](https://img.shields.io/badge/Entra%20ID-15803d?style=flat-square&labelColor=0a0d11)
![Active Directory](https://img.shields.io/badge/Active%20Directory-b45309?style=flat-square&labelColor=0a0d11)

**Platforms**

_Virtualization & storage_

![VMware](https://img.shields.io/badge/VMware-2563eb?style=flat-square&logo=vmware&logoColor=white&labelColor=0a0d11)
![NetApp](https://img.shields.io/badge/NetApp-15803d?style=flat-square&logo=netapp&logoColor=white&labelColor=0a0d11)

_Operating systems_

![Windows](https://img.shields.io/badge/Windows-b45309?style=flat-square&labelColor=0a0d11)
![Ubuntu](https://img.shields.io/badge/Ubuntu-2563eb?style=flat-square&logo=ubuntu&logoColor=white&labelColor=0a0d11)
![Red Hat](https://img.shields.io/badge/Red%20Hat-15803d?style=flat-square&logo=redhat&logoColor=white&labelColor=0a0d11)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-b45309?style=flat-square&logo=kalilinux&logoColor=white&labelColor=0a0d11)

_Cloud_

![AWS](https://img.shields.io/badge/AWS-2563eb?style=flat-square&labelColor=0a0d11)
![Azure](https://img.shields.io/badge/Azure-15803d?style=flat-square&labelColor=0a0d11)

**Containers & DevOps**

![Docker](https://img.shields.io/badge/Docker-2563eb?style=flat-square&logo=docker&logoColor=white&labelColor=0a0d11)
![Podman](https://img.shields.io/badge/Podman-15803d?style=flat-square&logo=podman&logoColor=white&labelColor=0a0d11)
![Kubernetes](https://img.shields.io/badge/Kubernetes-b45309?style=flat-square&logo=kubernetes&logoColor=white&labelColor=0a0d11)
![GitHub](https://img.shields.io/badge/GitHub-2563eb?style=flat-square&logo=github&logoColor=white&labelColor=0a0d11)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-15803d?style=flat-square&logo=githubactions&logoColor=white&labelColor=0a0d11)

**Frameworks**

![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-15803d?style=flat-square&labelColor=0a0d11)
![CIS Benchmarks & Controls](https://img.shields.io/badge/CIS%20Benchmarks%20%26%20Controls-2563eb?style=flat-square&labelColor=0a0d11)
![CISA CPG](https://img.shields.io/badge/CISA%20CPG-b45309?style=flat-square&labelColor=0a0d11)
![OWASP Top 10](https://img.shields.io/badge/OWASP%20Top%2010-15803d?style=flat-square&logo=owasp&logoColor=white&labelColor=0a0d11)
![ISO 27001](https://img.shields.io/badge/ISO%2027001-2563eb?style=flat-square&labelColor=0a0d11)
![NIS2](https://img.shields.io/badge/NIS2-b45309?style=flat-square&labelColor=0a0d11)
![OpenSSF Scorecard](https://img.shields.io/badge/OpenSSF%20Scorecard-15803d?style=flat-square&labelColor=0a0d11)

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

[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/blindtk/blindtk/badge)](https://securityscorecards.dev/viewer/?uri=github.com/blindtk/blindtk)

<div align="center">

<img src="./assets/streak.svg" alt="Daniel Malaco's GitHub contribution streak" />

<img src="./assets/trophies.svg" alt="Daniel Malaco's GitHub profile trophies" />

<img src="./assets/stars-given.svg" alt="Number of repositories Daniel Malaco has starred on GitHub" />

</div>

<details>
<summary>How these stats are generated</summary>

Banner, contribution streak, trophies and the starred-repos count are
generated weekly by
[`.github/workflows/update-profile-widgets.yml`](.github/workflows/update-profile-widgets.yml)
and committed to `assets/` — no live third-party endpoint is queried when
someone loads this profile.

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

</details>

Public activity here is a fraction of the work — most of it is internal
infrastructure, not public code. Formal certifications aren't tracked
here either — those live on [Credly](https://www.credly.com/users/daniel-malaco/badges),
linked again under Contact.

## Contact

[![Website](https://img.shields.io/badge/Website-danielmala.co-15803d?style=flat-square&labelColor=0a0d11)](https://danielmala.co)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-danielmalaco-2563eb?style=flat-square&labelColor=0a0d11)](https://www.linkedin.com/in/danielmalaco)
[![Email](https://img.shields.io/badge/Email-me%40danielmala.co-b45309?style=flat-square&logo=mailru&logoColor=white&labelColor=0a0d11)](mailto:me@danielmala.co)
[![Credly](https://img.shields.io/badge/Credly-badges-15803d?style=flat-square&logo=credly&logoColor=white&labelColor=0a0d11)](https://www.credly.com/users/daniel-malaco/badges)
