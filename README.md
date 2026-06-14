<h1 align="center">João Victor Caliman</h1>

<p align="center">
  <em>Full-stack engineer (TypeScript · Bun) building live, AI-assisted platforms for collaborative storytelling.</em>
</p>

<p align="center">
  🇧🇷 Brazil &nbsp;·&nbsp; @ Deloitte &nbsp;·&nbsp; <code>@masoria</code> on Discord
</p>

<p align="center">
  <a href="https://archive.masoria-universe.com"><img src="https://img.shields.io/badge/Arquivo_Masoria-Live_site-0A0A0A?style=for-the-badge" alt="Live site" /></a>
  <a href="https://discord.gg/ansenfall"><img src="https://img.shields.io/badge/Discord-ansenfall-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="mailto:sum2to7@gmail.com"><img src="https://img.shields.io/badge/Email-sum2to7@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/jvcaliman/"><img src="https://img.shields.io/badge/LinkedIn-jvcaliman-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center"><sub><i>"O outono chegou e jamais foi embora."</i> — Ansenfall: Ascensão</sub></p>

---

## 🍂 Currently building — [Arquivo Masoria](https://archive.masoria-universe.com)

A **live, full-stack platform** for a collaborative roleplaying universe — a public, read-only **archive** of narrative arcs, characters, and the *panteão de Ascensão*, written by a community of authors.

**Live → [archive.masoria-universe.com](https://archive.masoria-universe.com)** &nbsp;·&nbsp; **Community → [discord.gg/ansenfall](https://discord.gg/ansenfall)**

Powered by a private Bun monorepo:

| Layer | Stack |
| --- | --- |
| **Web** | Next.js 16 · React 19 (RSC) |
| **API** | Bun · Hono · Drizzle |
| **Realtime** | `Bun.serve` WebSocket fan-out |
| **Bot** | Discord — character proxy (*falas*) · creator wizard · role menus |
| **Engine** | Framework-agnostic, zod-only combat & crafting |

…all on **PostgreSQL + Docker**, shipped with a multi-agent, **AI-assisted workflow** (Claude Code + Codex + open agent [skills](https://skills.sh)).

## 🦖 Recently shipped — Primord Survival Dashboard

A members-only control panel for a self-hosted *The Isle: Evrima* community — Steam sign-in, live server ops, dinosaur storage, a live map, a 3D skin studio, and staff admin tooling.

**Live (members-only) → [painel.primord-oficial.com](https://painel.primord-oficial.com)**

| Layer | Stack |
| --- | --- |
| **Web** | Next.js 15 · React · Three.js (3D Skin Studio) |
| **Auth** | Auth.js / NextAuth 5 — Steam sign-in, SteamID64 identity |
| **Services** | TypeScript monorepo (pnpm) — API · RCON daemon · Discord bot · log-tailer |
| **Integration** | Native **C++** helper for live game-server control |
| **Infra** | PostgreSQL · Docker · Cloudflare Tunnel |

A six-app monorepo wiring a Next.js dashboard to a live game server.

## 🛠 Selected work

| Project | What it is |
| --- | --- |
| **[RenPy-WeaponPlugin](https://github.com/sum117/RenPy-WeaponPlugin)** ⭐ | Interactive weapon system (shooting · reloading) for the **Ren'Py** visual-novel engine |
| **[trinity-discordx](https://github.com/sum117/trinity-discordx)** | *"Discord Roleplaying. Redefined."* — a feature-rich RP bot (discordx · TypeScript) |
| **[CantYouSeeImBusy](https://github.com/sum117/CantYouSeeImBusy)** | **C# RimWorld mod** (live on the Steam Workshop) — keeps colonists focused in combat |
| **[the-conductor](https://github.com/sum117/the-conductor)** | Self-hosted Discord **music bot** — Bun · yt-dlp · ffmpeg · Docker |
| **[masoria-parser](https://github.com/sum117/masoria-parser)** | The little visual-novel parser where *Masoria* began |

**Open source — merged PRs:** **[oven-sh/bun](https://github.com/oven-sh/bun/pull/5513)** &nbsp;·&nbsp; **[discordx](https://github.com/discordx-ts/discordx/pull/886)** (pagination guard) &nbsp;·&nbsp; **[botlabs-gg/yagpdb](https://github.com/botlabs-gg/yagpdb/pull/1656)** (CodeMirror panel editor).

## 🧰 Toolbox

**Languages**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

**Web & API**  
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

**Runtime & Data**  
![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Bots · Realtime · Game**  
![discord.js](https://img.shields.io/badge/discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white)
![Ren'Py](https://img.shields.io/badge/Ren%27Py-663399?style=for-the-badge)

**Workflow**  
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

## 📊 Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sum117&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=tokyonight" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sum117&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sum117&hide_border=true&theme=tokyonight" alt="Streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sum117/sum117/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sum117/sum117/output/github-snake.svg" />
    <img alt="My contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/sum117/sum117/output/github-snake.svg" />
  </picture>
</p>

<!-- Snake auto-regenerates every 12h via .github/workflows/snake.yml → output branch. Private contributions included (toggle enabled in profile settings). -->

---

<p align="center"><sub>🔢 The handle is a numerology thing. &nbsp;·&nbsp; <i>Building worlds, one commit at a time.</i></sub></p>
