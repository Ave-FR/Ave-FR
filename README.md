<picture><source media="(prefers-color-scheme: dark)" srcset="./banner-dark.svg"><img src="./banner-light.svg" alt="Ave Corp: websites and custom tools for small businesses, by Rémy Agez" width="100%"></picture>

**Ave Corp** builds fast websites and custom tools for small businesses: clear pricing, a fixed scope, and one person you talk to from the first call to the launch.

I'm **Rémy Agez**, the founder, and a first-year master's (M1) engineering student at JUNIA ISEN. Ave Corp is my company, registered in October 2026.

Behind the scenes I run my own production system: specialised AI agents that draft, code and check, a shared memory they read before every task, and reviews at every step. They speed up the work; I decide, check and ship.

### What I'm building

| Project | What it is | Stack |
|---|---|---|
| **Agent Office** | The dashboard that runs the agents: live missions, token budget guard, project costs, night runs with a morning review, phone alerts, a map of the shared memory. | Next.js 16 · React · TypeScript · SSE |
| **Stella** | Voice copilot for the PC: wake word, local speech-to-text, arranges windows across screens, learns routines. Asks out loud before anything sensitive. | Python · faster-whisper · Edge TTS · Claude |
| **Mail assistant** | Reads the inbox, labels and archives the noise, drafts replies with a per-contact memory I can edit. A mail only leaves when I click send. | Gmail API · Next.js · Claude |
| **Agent harness** | 49 agents and 67 skills sharing one workflow (spec, plan, build, test, review), synced across machines and covered by tests. | Node.js · Python · Claude Code |
| **Shared memory** | An Obsidian vault the agents read before work and write to after, so no session starts from zero. | Markdown · Python |
| **Video and montage engine** | Studies a reference edit (cuts, effects, music sync, grading), then builds new edits in the same style, scored by an independent judge. | Python · ffmpeg · OpenCV |
| **Small-business sites** | Fast static sites for local trades: SEO, structured data, accessibility first. | HTML/CSS · Cloudflare Pages |

<sub>Repositories are private. Happy to walk through the code.</sub>

### First open-source tool, in progress

**piege-ia** (working name) finds hidden prompt injections in a document before you hand it to an AI: instructions in white or tiny text, invisible characters, text tucked in alt tags. A defensive check, MIT licence, README in French and English. Not public yet.

### How I work

- **Spec before code.** Every non-trivial feature gets a written plan that another agent challenges before anyone builds it.
- **Evidence over confidence.** Done means tests ran and a screenshot was checked, not that an agent said so.
- **Small diffs.** The smallest change that fully solves the problem, with a test for any new logic.
- **Human in the loop.** Anything that leaves the machine (a mail, a post, a payment) waits for my click.
- **Cost-aware.** Every token is tracked per project; a guard stops runs that blow the budget.

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white)

### Contact

[contact@avecorp.fr](mailto:contact@avecorp.fr)

<sub>En français : élève ingénieur à JUNIA ISEN et fondateur d'Ave Corp, je réalise des sites et des outils sur mesure pour les petites entreprises. Écrivez-moi à la même adresse.</sub>
