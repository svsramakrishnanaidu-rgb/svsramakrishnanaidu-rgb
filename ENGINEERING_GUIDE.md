# Developer portfolio — Architecture and project review index

This companion to the [profile README](README.md) provides a technical reading route through the six project repositories. It distinguishes software applications, independent prototypes and research specifications. It is not a claim that every feature is live or that all projects share a backend.

## Portfolio relationship map

~~~mermaid
flowchart TD
 P[Developer portfolio]
 P --> H[HYDRO AI - orchestration application]
 P --> D[DHRUVA AI - agriculture]
 P --> L[LEO.AI - civic prototype]
 P --> W[LIMITLESS - wellness education]
 P --> F[FinTrack - expense journal]
 P --> A[LEO 2.0 - agent specification]
~~~

## Technical reading paths

| Repository | Suggested reviewer focus |
| --- | --- |
| [Hybridai](https://github.com/svsramakrishnanaidu-rgb/Hybridai) | Model routing, claim evaluation, voice/vision and provider boundaries |
| [dhruvaai](https://github.com/svsramakrishnanaidu-rgb/dhruvaai) | React/TanStack route organization and agricultural data quality |
| [leo-ai](https://github.com/svsramakrishnanaidu-rgb/leo-ai) | Browser-local report lifecycle and client/server security boundary |
| [limitless](https://github.com/svsramakrishnanaidu-rgb/limitless) | Health education, server-side provider failover and privacy |
| [fin-tracker](https://github.com/svsramakrishnanaidu-rgb/fin-tracker) | Flutter UI, local expense storage and integer arithmetic |
| [leo2.0ai](https://github.com/svsramakrishnanaidu-rgb/leo2.0ai) | Planned agent architecture and reference permission policy |

## Shared engineering principles

~~~mermaid
flowchart LR
 A[Problem] --> B[Scope and requirements]
 B --> C[Architecture and trust boundaries]
 C --> D[Implementation]
 D --> E[Tests and measured evidence]
 E --> F[Documentation]
 F --> G[Review and iteration]
~~~

Projects should be evaluated according to their actual scope. A local prototype can demonstrate useful design without providing production infrastructure. A specification can demonstrate architectural thinking without constituting a shipped application. A successful build proves compilation for a particular environment, not real-world accuracy or security.

For AI projects, explain which component calls models, how failure is represented, where credentials are stored and what data leaves the device. For domain applications, identify which information is educational and which requires professional validation. For mobile and web projects, show real interface screenshots tied to a reproducible version. Use source links instead of unsupported user counts, performance claims or professional credentials.

## Proposed portfolio maintenance

Review project status whenever functionality changes. Keep a short profile README and place deeper technical explanations in individual repositories. Track broken links, dependency risks, CI status and unresolved security concerns. Add new case studies only when their scope and attribution are clear. Retain user work and avoid synthetic contributions or unnecessary commits.
