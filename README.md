## Hi there ![wave](https://github.com/user-attachments/assets/e8cdbc56-3f90-46df-8f91-2212e32f7128)

I'm Bastián, a software engineer in Santiago, Chile. [crizoz.github.io](https://crizoz.github.io)

I work at [Makana](https://makana.cl), a wellness startup, where I build the product across mobile, backend and data:
a Flutter app, a Ruby on Rails and PostgreSQL backend on Google Cloud, the wearable integrations that bring sleep,
recovery and workout data in, and the analytics that tell us whether a feature landed.

I also own how the team works with AI coding agents, which is the part I would rather talk about.

#### Agents, in practice

- **A Claude Code plugin marketplace for the team.** Skills namespaced per repo for the product board, backend PR
  review, mobile releases, funnel queries and client decks, so everyone gets the same workflow instead of a private
  prompt. A `SessionStart` hook updates every machine, so a push to `main` lands in the next session anyone opens.
- **Hooks where a skill is not enough.** A skill only loads when the agent decides to invoke it, and the person who
  just merged a PR has no reason to think about the board. That rule lives in a hook that always runs.
- **MCP servers**, for the product and for the team. The product one is Ruby on Cloud Run, with OAuth introspection
  against our Rails backend so each request carries its own user. The internal ones let people ask questions of our
  data without touching a database.
- **Tooling for parallel agents.** A build queue that serializes Flutter jobs, because several agents on one laptop
  will happily take the machine down fighting over cores.
- **People, not only pipelines.** Our nutritionist and our psychologist own their own modules and ship changes through
  agents. Neither of them writes code.

#### Things I have built

- [**Meridian**](https://github.com/crizoz/meridian-claude-impact-lab) ([demo](https://meridian-claude-impact-lab.vercel.app)).
  A multi-agent system over Chilean securities and banking regulation. Second place at Anthropic's Claude Impact Lab,
  the first AI financial inclusion hackathon in Latin America.
- [**Vitals**](https://github.com/crizoz/vitals). A native macOS menu bar app for your Mac's vitals and your real
  Claude usage limits. Swift and SwiftUI.
- [**Fleet**](https://github.com/crizoz/fleet). A live view of every Claude Code session running in your terminals,
  on the desktop, in the menu bar and as a widget.
- [**AI Bootcamp 360**](https://github.com/crizoz/bootcamp-ia-react). An educational platform I co-managed and built
  for a university AI program, on the OpenAI and Gemini APIs.

Day to day I write TypeScript, Dart, Ruby, Python, Swift and SQL. I am finishing my degree in Computer Engineering at
Universidad Andrés Bello, graduating in 2027.

#### Let's connect!
[<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%230E76A8.svg?&style=for-the-badge&logo=LinkedIn&logoColor=white" />](https://linkedin.com/in/bastiancarriz)
