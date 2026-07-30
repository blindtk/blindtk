<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0a0d11,100:3ddc84&height=170&section=header&text=Daniel%20Malaco&fontColor=e6edf3&fontSize=42&desc=Information%20Security%20Engineer%20%C2%B7%20Porto%2C%20PT&descSize=16&descAlignY=68&animation=false" />
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0d11,100:3ddc84&height=170&section=header&text=Daniel%20Malaco&fontColor=e6edf3&fontSize=42&desc=Information%20Security%20Engineer%20%C2%B7%20Porto%2C%20PT&descSize=16&descAlignY=68&animation=false" alt="Banner: Daniel Malaco, Information Security Engineer, Porto, Portugal" />
</picture>

Information Security Engineer designing and operating the security
architecture for critical road infrastructure in Portugal. Came up through
networks before moving into security.

## What I do

- Design, deploy and operate the security architecture for critical road
  infrastructure in Portugal: NGFW, AV/EDR, vulnerability analysis, SIEM,
  IAM, WAF, secure email gateway.
- Run the full detection cycle end to end — from designing the control to
  analyzing the event and closing the incident through ITSM.
- Bring an offensive perspective into defensive work — internal penetration
  testing experience and four CTFs won feed directly back into how I design
  detections.
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

## Projects

| Project | Why it's there |
| --- | --- |
| **[danielmala.co](https://github.com/blindtk/personal-site)** — personal site | Astro, zero client-side JavaScript by default, content kept out of the codebase (markdown/JSON), bilingual PT/EN from shared components. Ships a strict Content-Security-Policy with no `'unsafe-inline'`, security headers, and a published responsible-disclosure policy — with an *Evidence* page that deep-links commits, workflows, and a live header scan. Hosted on Cloudflare Pages; the one piece that genuinely needs a server lives isolated in a Cloudflare Worker. |
| **Honeypot** — same monorepo, inside the Worker | Decoy endpoints (`/wp-login.php`, `/.env`, `/.git/config`, `/admin`, `/phpmyadmin/`) that log automated scanning and hand back the usual 404. Privacy by construction: **no IP is ever stored** — only country (`cf-ipcountry`), ASN, and the path, timestamped to the nearest 5 minutes; the rate-limit key is a salted, rotating, truncated SHA-256. A test enforces that the IP never reaches KV or the logs. Each decoy is tagged with its MITRE ATT&CK technique and cross-referenced against the CISA KEV catalog. |
| **ATT&CK heatmap** | All 14 Enterprise tactics mapped to the techniques I cover defensively, each with the tool or experience behind it and an honest level (`production` vs. `lab/one-off`). The CV, written in the industry's native language. |
| **Client-side tools** — danielmala.co/tools | Subnet calculator, hash generator and others, all running in-browser. The three that genuinely need a server (compromised-password check via k-anonymity, header self-scan, "what the server sees of you") are marked with a *requires server* badge — never disguised as client-side. |
| **star-organizer** | Python CLI that turns a chaotic GitHub stars list into a browsable catalog by category (markdown + JSON), with a weekly GitHub Action. Feeds the site's link library. The underlying `github-stars` repo is private, so it isn't linked here — see the site's link page for the output. |
| **Homelab** | k3s cluster on Raspberry Pi, at home. The test bed for everything before it goes anywhere near production. |

## Statistics

<div align="center">

<img src="./assets/github-stats.svg" alt="Daniel Malaco's GitHub stats" width="49%" />
<img src="./assets/top-langs.svg" alt="Daniel Malaco's most-used languages on GitHub" width="49%" />

<img src="https://streak-stats.demolab.com/?user=blindtk&hide_border=true&background=0a0d11&border=161c28&stroke=161c28&ring=3ddc84&fire=f5b544&currStreakLabel=3ddc84&currStreakNum=e6edf3&sideNums=e6edf3&dates=8593a5&sideLabels=8593a5" alt="Daniel Malaco's GitHub contribution streak" />

<img src="./assets/trophies.svg" alt="Daniel Malaco's GitHub profile trophies" />

<img src="./assets/stars-given.svg" alt="Number of repositories Daniel Malaco has starred on GitHub" />

</div>

Stats, top languages, trophies and the starred-repos count are generated
weekly by
[`.github/workflows/update-profile-widgets.yml`](.github/workflows/update-profile-widgets.yml)
and committed to `assets/` — no live third-party endpoint is queried when
someone loads this profile. The streak card still calls
`streak-stats.demolab.com` directly, which is up and stayed out of scope
for self-hosting.

Public activity here is a fraction of the work — most of it is internal
infrastructure, not public code.

## Contact

[![Website](https://img.shields.io/badge/Website-danielmala.co-3ddc84?style=flat-square&labelColor=0a0d11)](https://danielmala.co)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-danielmalaco-4aa8ff?style=flat-square&logo=linkedin&logoColor=white&labelColor=0a0d11)](https://www.linkedin.com/in/danielmalaco)
[![Email](https://img.shields.io/badge/Email-me%40danielmala.co-f5b544?style=flat-square&logo=maildotru&logoColor=white&labelColor=0a0d11)](mailto:me@danielmala.co)
[![Credly](https://img.shields.io/badge/Credly-badges-3ddc84?style=flat-square&labelColor=0a0d11)](https://www.credly.com/users/daniel-malaco/badges)

<details>
<summary><strong>Português (Europeu)</strong></summary>

Information Security Engineer a desenhar e operar a arquitetura de
segurança de infraestrutura crítica rodoviária em Portugal. Veio das redes
antes de passar para a segurança.

### O que faço

- Desenho, deployment e operação da arquitetura de segurança da
  infraestrutura crítica rodoviária em Portugal: NGFW, AV/EDR, análise de
  vulnerabilidades, SIEM, IAM, WAF, security email gateway.
- Ciclo completo de deteção: do desenho do controlo à análise do evento e
  ao fecho do incidente em ITSM.
- Traz uma perspetiva ofensiva para o trabalho defensivo — experiência em
  testes de intrusão internos e quatro CTFs ganhos alimentam diretamente o
  desenho de deteções.

</details>

<div align="right">

<img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fblindtk&countColor=%233ddc84&style=flat-square&labelColor=%230a0d11" alt="Visitor count badge for this GitHub profile" />

</div>
