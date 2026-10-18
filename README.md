<img src="./banner.svg" alt="Ave Corp: a one-person company, run by a team of AI agents" width="100%">

I build the tooling that lets AI agents handle the day-to-day of a small company: planning, coding, reviewing, shipping, and remembering what happened yesterday. The company is me; the staff is ~45 specialised Claude Code agents.

### What I'm building

| Project | What it is | Stack |
|---|---|---|
| **Agent Office** | Pixel-art dashboard that drives the agents: live missions, token budget guard, project costs, night runs with a morning review. | Next.js 16 · React · TypeScript · SSE |
| **Agent harness** | ~45 agents and ~50 skills with one shared workflow (spec → plan → build → test → review), synced across machines and checked by tests. | Node.js · Python · Claude Code |
| **Shared memory** | An Obsidian vault the agents read before work and write to after, so no session starts from zero. | Markdown · Python |
| **Small-business sites** | Fast static sites for local trades: SEO, structured data, accessibility first. | HTML/CSS · Cloudflare Pages |

<sub>Repositories are private. Happy to walk through the code.</sub>

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white)

### How I work

- **Spec before code.** Every non-trivial feature gets a written plan that another agent challenges before anyone builds it.
- **Evidence over confidence.** Done means tests ran and a screenshot was checked, not that an agent said so.
- **Small diffs.** The smallest change that fully solves the problem, with a test for any new logic.
- **Cost-aware.** Every token is tracked per project; a guard stops runs that blow the budget.
