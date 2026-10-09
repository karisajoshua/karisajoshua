<div align="center">

# `joshua@github:~$ whoami`

## Joshua Karisa

**Software Engineer · Security-Conscious Systems · Cloud · AI & Automation**

`Building secure, production-minded digital systems.`

[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=githubpages&logoColor=white)](https://karisajoshua.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111827?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joshua-karisa-b0b684163/)
[![Texcortech](https://img.shields.io/badge/Texcortech_Systems-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://texcortech.co.ke/)

</div>

---

### `$ cat engineering_profile.txt`

I build **web applications, APIs, business platforms and security-conscious systems**. My work spans full-stack engineering, cloud delivery, integrations, automation and applied security.

I am also building hands-on capability in **LLM engineering and technical AI safety**, including retrieval-augmented generation (RAG), vector search, controlled agent/tool calling, evaluations, observability, security and reliable deployment. I distinguish production experience from areas I am actively learning.

### `$ ./engineering-governance --explain`

I am interested in **open-source projects focused on autonomous engineering governance, software security, AI-assisted engineering, and human oversight of automated systems**. My current work explores how specialized tools can observe repository health, identify engineering and security deficiencies, propose controlled and reviewable improvements, independently evaluate those proposed changes using CI, risk and security evidence, and preserve human authority over consequential decisions. Projects such as **ProjectPulse, RepoGuardian, PRPilot and SentinelRAG** are practical experiments in this direction, helping me explore separation of duties, least-privilege automation, explainable recommendations, measurable software-quality improvement and responsible use of autonomous engineering workflows.

| Bot | Role | What it does | What it cannot do |
| --- | --- | --- | --- |
| [**ProjectPulse**](https://github.com/karisajoshua/project-pulse) | Observer | Measures repository health across CI, tests, documentation, security policy, licensing, contribution guidance and maintenance signals | Does not remediate repositories |
| [**RepoGuardian**](https://github.com/karisajoshua/repo-guardian) | Remediator | Converts supported findings into deterministic remediation plans and reviewable patches on isolated `repoguardian/*` branches | Cannot silently write fixes to `main` or merge its own work |
| [**PRPilot**](https://github.com/karisajoshua/Pr-pilot) | Independent reviewer | Examines proposed changes, CI evidence, branch isolation, changed paths and security-sensitive scope, then issues an explainable recommendation | Cannot merge a pull request or replace human approval |

#### How the bots work together

```text
Repository
    │
    ▼
ProjectPulse ── observe / score / explain
    │
    │ structured health findings
    ▼
RepoGuardian ── plan / patch / open Draft PR
    │
    │ reviewable proposal on isolated branch
    ▼
PRPilot ─────── independent CI / risk / security review
    │
    │ approve recommendation / changes recommended /
    │ manual review required
    ▼
Human ───────── merge or reject
    │
    ▼
ProjectPulse ── measure again and verify improvement
```

#### A live example

Suppose ProjectPulse detects that a repository is missing a security policy. ProjectPulse reports the failed control but does not modify the repository. RepoGuardian can map that supported finding to a deterministic `SECURITY.md` patch, create an isolated remediation branch, and open a **Draft Pull Request**. The PR event activates PRPilot, which independently checks the proposal and available CI/risk evidence. PRPilot posts an advisory recommendation, but the process still stops at the human approval boundary. After an approved change is merged, ProjectPulse can score the repository again to determine whether the intervention produced a measurable improvement.

**Separation of duties is intentional:** the bot that measures the problem is not the bot that fixes it; the bot that proposes the fix is not the bot that reviews it; and no bot is the final merge authority.

> **Current integration status:** ProjectPulse and RepoGuardian are implemented, and PRPilot's event-driven advisory path is under live validation. The repositories and pull requests remain the source of truth for operational status.

### `$ current_focus --tree`

```text
engineering/
├── full-stack-systems
├── application-security
├── cloud-and-delivery
├── APIs-and-integrations
├── AI-and-automation
│   ├── LLM-APIs-and-RAG
│   ├── vector-search
│   └── controlled-agent-tool-calling
└── technical-AI-safety
    ├── evaluations
    ├── security-and-red-teaming
    └── reliability-and-oversight
```

### `$ ls ./toolbox`

**Applications & Backend**

![React](https://skillicons.dev/icons?i=react,nodejs,java,spring,ts,js,supabase&theme=dark)

**Cloud, DevOps & Infrastructure**

![Cloud](https://skillicons.dev/icons?i=aws,vercel,docker,kubernetes,terraform,ansible,github,git&theme=dark)

**Security & Engineering**

`Burp Suite` · `Wireshark` · `Nmap` · `Nessus` · `Wazuh` · `Splunk` · `REST APIs` · `CI/CD`

### `$ ./featured-projects --engineering`

| Project | Engineering focus | What it demonstrates |
| --- | --- | --- |
| **Zest Insurance Management System** | InsurTech / full-stack integration engineering | Multi-agency insurance workflows, customer and policy management, DMVIC integration foundation, certificate processing and automation under development; React, TanStack Start and Supabase. [Technical documentation](https://github.com/karisajoshua/pixel-perfect-clone-94206-250aa43a/tree/main/docs) (repository access may be restricted) |
| [**SentinelRAG**](https://github.com/karisajoshua/sentinel-rag) | Applied AI / LLM engineering | Python, FastAPI, RAG, embeddings, pgvector, evidence-grounded Q&A, controlled tool boundaries, evaluation, observability and containerized deployment architecture |
| [**Sprints**](https://github.com/karisajoshua/sprints) | Project / program systems | Authenticated workspaces, organization context, Scrum/startup/NGO dashboards, projects, teams and invitations |
| [**Africa Vision Workspace**](https://github.com/karisajoshua/africa-vision-workspace) | Collaborative SaaS | Protected project, task, team, document, calendar, reporting, messaging and department workflows |
| [**Symbiont**](https://github.com/karisajoshua/symbiont) | Data / AI prototype | Geographic reporting, Supabase report feeds and AI-assisted sentiment analysis |
| [**MalwareScannerService**](https://github.com/karisajoshua/MalwareScannerService) | Security engineering | Malware-scanning implementation and security-oriented engineering |
| [**Simple Encryption Tool**](https://github.com/karisajoshua/Simple-Encryption-Tool) | Applied security | Encryption implementation and technical documentation |
| [**Texcortech Systems**](https://github.com/karisajoshua/texcortech) | Production web engineering | Multi-page company experience, case-study routing and Supabase-backed server functions |

> Repositories are the source of truth for implementation status. Prototype functionality is identified as such rather than presented as production capability.

### `$ project-pulse --portfolio`

<!-- PROJECT-PULSE:START -->
> Automated, read-only repository-health snapshot powered by [ProjectPulse](https://github.com/karisajoshua/project-pulse).

**Bot status:** Authorization warning — account credential returned no private repositories

**32** maintained repositories · **32 public** · **0 private** · **44/100** combined observable health

Portfolio distribution: **2** excellent · **0** healthy · **8** need attention · **22** critical · Public-only average: **44/100**

| Public repository | Health | Status |
| --- | ---: | --- |
| [codesentryx](https://github.com/karisajoshua/codesentryx) | **100/100** | Excellent |
| [project-pulse](https://github.com/karisajoshua/project-pulse) | **100/100** | Excellent |
| [symbiont](https://github.com/karisajoshua/symbiont) | **63/100** | Needs attention |

<sub>Private repository identities are never published. Account-level authorization is required for private aggregation. Observable score covers documentation, licensing, CI, security policy, contribution guidance and recent maintenance. It does not execute repository code. Updated 2026-10-05 UTC.</sub>
<!-- PROJECT-PULSE:END -->

### `$ github --stats`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=karisajoshua&show_icons=true&hide_border=true&theme=github_dark&rank_icon=github" alt="Joshua Karisa GitHub statistics" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=karisajoshua&layout=compact&hide_border=true&theme=github_dark" alt="Joshua Karisa top languages" />

<img src="https://streak-stats.demolab.com?user=karisajoshua&theme=github-dark-blue&hide_border=true" alt="Joshua Karisa GitHub streak" />

</div>

### `$ cat principles.md`

- **Security by design** — protect credentials, data boundaries and privileged operations.
- **Evidence over claims** — let code, tests and documentation demonstrate capability.
- **Reproducibility** — document setup, architecture and important engineering decisions.
- **Traceability** — use version control, review and automation to make changes auditable.
- **Production thinking** — design for reliability, maintainability and observable failure modes.
- **Responsible AI** — evaluate limitations and safety properties rather than assuming model reliability.

### `$ ./ai-safety --status learning+building`

My software engineering background gives me a practical entry point into AI reliability and security. Through **SentinelRAG**, I am applying that foundation to RAG pipelines, evidence-grounded LLM responses, vector retrieval, controlled tool boundaries, evaluation and observability while continuing to develop capability in **AI security/red-teaming, research engineering, and technical approaches to control and oversight**.

These are active learning and contribution goals—not claims of completed AI-safety research credentials.

### `$ ./contributions --visualize`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/karisajoshua/karisajoshua/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/karisajoshua/karisajoshua/output/github-contribution-grid-snake.svg">
  <img alt="Joshua Karisa contribution graph animation" src="https://raw.githubusercontent.com/karisajoshua/karisajoshua/output/github-contribution-grid-snake.svg">
</picture>

</div>

### `$ connect --with joshua`

<div align="center">

[**Portfolio**](https://karisajoshua.github.io/) · [**LinkedIn**](https://www.linkedin.com/in/joshua-karisa-b0b684163/) · [**Texcortech Systems**](https://texcortech.co.ke/) · [**GitHub**](https://github.com/karisajoshua)

`open_to = ["software engineering", "security", "AI systems", "technical collaboration"]`

</div>
