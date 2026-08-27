<div align="center">

<img src="https://capsule-render.com/api?type=waving&color=gradient&customColorList=6,11,20&height=250&section=header&text=Jeferson%20Zelaya&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full%20Stack%20Developer%20%C2%B7%20AI%20Agent%20Orchestration&descAlignY=52&descSize=20" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=F72585,7209B7,3A0CA3,4361EE,4CC9F0&center=true&vCenter=true&multiline=true&width=700&height=90&lines=Full+Stack+Developer+%7C+TypeScript+%C2%B7+NestJS+%C2%B7+Next.js;I+build+tooling+that+orchestrates+AI+coding+agents;Multi-tenant+SaaS%2C+REST+APIs%2C+PostgreSQL;Informatica+Empresarial+%40+UCR+-+graduating+Oct+2026" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jefersonzelayaestrada/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jeferson.zelayae@gmail.com)
[![Location](https://img.shields.io/badge/Costa%20Rica-4CC9F0?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

<img src="https://komarev.com/ghpvc/?username=JasvlL&label=Profile%20Views&color=4361ee&style=for-the-badge" />
<img src="https://img.shields.io/github/followers/JasvlL?label=Followers&style=for-the-badge&color=7209b7" />
<img src="https://img.shields.io/badge/Open%20to%20work-Available-2ea043?style=for-the-badge" />

</div>

<br/>

<img width="100%" src="https://capsule-render.com/api?type=rect&color=0:0d1b2a,100:1b263b&height=2"/>

## 🧑‍💻 About me

I build web applications end to end — data modelling, REST APIs, authentication and role-based access control, through to deployed interfaces. Most of my work is TypeScript over **NestJS** and **Next.js**, backed by **PostgreSQL** and **Prisma**.

Lately most of my own time goes into a narrower problem: **making autonomous AI coding agents verifiable enough to run unattended** — orchestration across providers, task isolation in separate git worktrees, and verifying what an agent claims it did against exit codes, real file diffs, and a build command, rather than taking its word for it.

```ts
const jeferson = {
  role:      "Full Stack Developer",
  studying:  "Informatica Empresarial @ Universidad de Costa Rica",
  graduates: "October 2026",
  focus:     ["Multi-tenant SaaS", "REST APIs", "AI agent orchestration"],
  stack:     ["TypeScript", "NestJS", "Next.js", "PostgreSQL", "Prisma"],
  languages: ["Spanish (native)", "English (C1)"],
  philosophy: "Always learning, always building",
};
```

<br/>

<img width="100%" src="https://capsule-render.com/api?type=rect&color=0:0d1b2a,100:1b263b&height=2"/>

## 🛠️ Tech stack

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=ts,js,py,java,php,cs,html,css&theme=dark)](https://skillicons.dev)

**Backend & Frameworks**

[![Backend](https://skillicons.dev/icons?i=nestjs,nodejs,express,laravel,prisma,dotnet&theme=dark)](https://skillicons.dev)

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=react,nextjs,angular,tailwind&theme=dark)](https://skillicons.dev)

**Databases**

[![Databases](https://skillicons.dev/icons?i=postgres,mysql,mongodb,firebase&theme=dark)](https://skillicons.dev)

**Tools & Infrastructure**

[![Tools](https://skillicons.dev/icons?i=git,github,docker,vercel,linux,postman,figma,vscode&theme=dark)](https://skillicons.dev)

**AI-augmented development**

![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-1a1a1a?style=for-the-badge)
![Codex](https://img.shields.io/badge/OpenAI%20Codex-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)

</div>

<br/>

<img width="100%" src="https://capsule-render.com/api?type=rect&color=0:0d1b2a,100:1b263b&height=2"/>

## 🚀 What I build

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Agent fleet orchestration

A hybrid multi-model orchestrator for AI coding agents, built around one premise: **an agent's word is not evidence.**

- Cheap deterministic fixes run without spending a single token
- Context is sliced down to what a task strictly needs before any model is invoked
- Every task is isolated in its own `git worktree`, so a bad run cannot contaminate the tree
- Every result is verified against exit codes, physical file diffs and a build/test command before a human ever sees it

`TypeScript` `Node.js` `Git internals`

</td>
<td width="50%" valign="top">

### 🌑 Cross-provider agent IDE

A terminal IDE that runs Claude and Gemini under a single orchestrator.

- An agent on one provider can delegate work to an agent on another
- The conversation survives the switch — no context lost when handing off between models
- Interactive IDE mode plus a single-turn non-interactive mode for scripting

`TypeScript` `CLI` `LLM APIs`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Multi-tenant SaaS platform

A platform for managing funding calls, applications, evaluations and business diagnostics — built for a client, currently in deployment.

- Monorepo separating web, API and worker services
- JWT authentication with sliding sessions
- Granular role-based access control across owner, evaluator and beneficiary roles
- Full audit trail — when a decision allocates money, "who changed this" has to be answerable
- Multi-tenant data isolation, with no physical deletion of functional records
- Specified before it was built: written requirements spec and architecture proposal

`NestJS` `Next.js` `PostgreSQL` `Prisma`

</td>
<td width="50%" valign="top">

### 🌳 Bosque Las Madres Biological Corridor

[![Live site](https://img.shields.io/badge/live-bosque--las--madres.vercel.app-2ea043?style=for-the-badge&logo=vercel&logoColor=white)](https://bosque-las-madres.vercel.app)

Official site for a biological corridor in Limón, Costa Rica. Requirements gathered directly with the corridor's coordination team, then designed, built and published from scratch.

- Catalogue of **177 bird species** — taxonomic filters, real-time search, birdsong audio, pagination
- Interactive map of the 4 observation trails
- **Lighthouse 94 performance · 98 SEO** — static rendering, image optimisation, a hand-rolled CSS design system

`Next.js 16` `React 19` `Leaflet`

</td>
</tr>
</table>

<div align="center">

*Also: a collaborative multi-agent system for real estate management — LLM routing through OpenRouter, live web search, and specialised legal and market-analysis agents triggered by @-mention. Early prototype.*

</div>

<br/>

<div align="center">

<sub>Some of the work above lives in private repositories. Happy to walk through architecture, trade-offs and code in a conversation.</sub>

</div>

<br/>

<img width="100%" src="https://capsule-render.com/api?type=rect&color=0:0d1b2a,100:1b263b&height=2"/>

## 📊 GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=JasvlL&show_icons=true&theme=radical&hide_border=true&count_private=true&bg_color=0d1117" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JasvlL&layout=compact&theme=radical&hide_border=true&bg_color=0d1117" width="30%"/>

<img src="https://streak-stats.demolab.com/?user=JasvlL&theme=radical&hide_border=true&background=0d1117" width="80%"/>

</div>

<br/>

## 🐍 Contribution graph

<div align="center">

<img src="https://raw.githubusercontent.com/JasvlL/JasvlL/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

<br/>

<img width="100%" src="https://capsule-render.com/api?type=rect&color=0:0d1b2a,100:1b263b&height=2"/>

<div align="center">

## 📫 Get in touch

Open to full-time roles — remote, or on-site in Costa Rica's Greater Metropolitan Area.

[![Email](https://img.shields.io/badge/jeferson.zelayae@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jeferson.zelayae@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jefersonzelayaestrada/)

</div>

<img src="https://capsule-render.com/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>
