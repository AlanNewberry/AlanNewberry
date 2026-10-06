# Alan Newberry

**Offensive Security · Application Security · Software Engineering**

[![Website](https://img.shields.io/badge/vandalsystems.com-111111?style=flat&logo=googlechrome&logoColor=white)](https://www.vandalsystems.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alan-newberry/)
[![Hack The Box](https://img.shields.io/badge/Hack_The_Box-9FEF00?style=flat&logo=hackthebox&logoColor=black)](https://profile.hackthebox.com/profile/019c39b9-27a5-70a1-9e95-e2207227f74e)

Software engineer with 3+ years of professional experience building web, mobile, and SaaS products. I focus on offensive security and application security, combining an attacker's perspective with practical knowledge of authentication, authorization, APIs, multi-tenant data isolation, and production infrastructure.

I build security tooling and reproducible proof-of-concepts for authorized research and lab environments.

## Selected security research

| Project | Focus |
|:--|:--|
| [CVE-2026-4480 — Samba print command injection](https://github.com/AlanNewberry/CVE-2026-4480-samba-print-command-injection-rce) | Unauthenticated command injection through Samba's `%J` print job substitution |
| [CVE-2026-3888 — snap-confine privilege escalation](https://github.com/AlanNewberry/CVE-2026-3888-snap-confine-privilege-escalation) | Local privilege escalation through a race condition and loader hijacking |
| [AD CS ESC1 template cloning](https://github.com/AlanNewberry/adcs-esc1-clone-certificate-template-privesc) | Active Directory Certificate Services privilege escalation |
| [Gitea/Gogs symlink to RCE](https://github.com/AlanNewberry/gitea-gogs-symlink-git-config-rce) | `.git/config` poisoning through repository-content APIs |
| [PyYAML to AWS CodeBuild escape](https://github.com/AlanNewberry/pyyaml-unsafe-deserialization-rce-aws-codebuild-escape) | Unsafe deserialization chained with a privileged container escape |
| [SOAP/WCF XXE file disclosure](https://github.com/AlanNewberry/soap-wcf-xxe-out-of-band-file-disclosure) | Out-of-band XXE exploitation and server-side file disclosure |

## Security tooling

| Project | Description |
|:--|:--|
| [Vandal](https://github.com/AlanNewberry/Vandal) | Web security scanner for reflected XSS, SQL injection, security headers, subdomain discovery, and historical URL collection |
| [Luna](https://github.com/AlanNewberry/Luna) | Modular REST API security scanner covering IDOR, authentication, SQL injection, XSS, HTTPS, and structured JSON reporting |
| [Astral Sniffer](https://github.com/AlanNewberry/Astral-Sniffer) | Packet capture and traffic analysis with protocol filters, PCAP export, and CSV/JSON statistics |
| [Good Luck](https://github.com/AlanNewberry/Good-Luck) | Multithreaded SYN, TCP, and UDP port scanner with banner grabbing and JSON output |
| [Pentest Reports](https://github.com/AlanNewberry/Pentest-Reports) | Web and API penetration-testing report templates using OWASP, PTES, CWE, and CVSS v3.1 |

## Technical focus

| | |
|:--|:--|
| **Security** | Web and API security, vulnerability research, exploitation, privilege escalation, network analysis, DFIR |
| **Engineering** | Authentication and authorization, REST APIs, RBAC, Row Level Security, multi-tenant systems, secure SDLC |
| **Languages** | Python, Bash, Go, JavaScript/TypeScript, Kotlin, Swift |
| **Infrastructure** | Docker, PostgreSQL, Redis, Supabase, Cloudflare, Vercel, Nginx |

## Product engineering

- **[Vulnex](https://vulnex.vandalsystems.com)** — Cybersecurity SaaS for breach exposure, compromised credentials, and typosquatting monitoring.
- **[Vandal Health](https://www.vandalsystems.com/vandal-health)** — Multi-tenant healthcare SaaS using RBAC, Row Level Security, REST APIs, and containerized deployment.
- **Healthcare interoperability API** *(private repository)* — OAuth2 Client Credentials, JWT, tenant isolation, Redis rate limiting, and security tests for exchanging sensitive clinical data.
- **[Fix!](https://www.fixarg.ar)** — Native iOS and Android applications with Firebase authentication, APNs/FCM, Mercado Pago, and production store releases.
- **[Lightmoon](https://lightmoon.com.ar)** — Social platform with Google OAuth, profiles, posts, comments, and reactions.
- **[RACE.COM](https://play.google.com/store/apps/details?id=com.racecom.balanzaapp)** — Android application communicating with motorsport scales through Bluetooth Low Energy.

Most professional source code is private due to client confidentiality.

## Labs and continuous training

**Hack The Box:** Hacker rank · Level 53 (Professional)<br>
**Progress:** 35 machines · 41 challenges · 12 Sherlocks

<details>
<summary>Selected Hack The Box work</summary>

### Machines

- **Hard:** Nimbus, Snapped, Ghostlink, Checkpoint
- **Medium:** Abducted, DanglingTree, Bedside, Layover, MakeSense, SmartHire, Principal, FireFlow, DevHub, Blurry
- **Easy:** Cohort, Touch, Management, TwoMillion, Kobold, Silentium, Orion, Nexus, Paperwork, Enigma, Connected, Reactor, Bashed, Irked, PermX, Networked, Luanne, Cap, Spectra, Lame

### Challenges

- **Web:** ReactOOPS, OpenSecret, Space Explorer, Sp00ky Theme, WayWitch, Armaxis, OnlyHacks, Evaluative, Spookifier, Flag Command, SpookyPass
- **DFIR/Forensics:** Primed for Action; UFO-1, Operation Blackout 2025: Phantom Check, CrownJewel-1/2, Reaper, Noxious, Campfire-1/2, Dream Job-1, BFT, Unit42, Brutus
- Additional work across crypto, reversing, OSINT, hardware, satellite, and quantum challenges

</details>

Additional practical training through Hack4u in ethical hacking, offensive Python, Linux administration, and professional Linux environments. English: B1 conversational, B2 reading/writing.

## Contact

- [Vandal Systems](https://www.vandalsystems.com/contact)
- [LinkedIn](https://www.linkedin.com/in/alan-newberry/)

> Security tools and proof-of-concepts in this profile are intended exclusively for authorized testing, research, and educational environments.
