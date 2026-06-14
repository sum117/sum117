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
  <a href="https://www.youtube.com/@ansenfall"><img src="https://img.shields.io/badge/YouTube-@ansenfall-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
</p>

<p align="center"><sub><i>"O outono chegou e jamais foi embora."</i> — Ansenfall: Ascensão</sub></p>

<p align="center"><b>🌐</b> &nbsp; 🇺🇸 English (default) &nbsp;·&nbsp; clique em ▸ para <b>🇧🇷 Português</b></p>

<details>
<summary>🇧🇷 &nbsp;<b>Ler o perfil em Português</b></summary>

### João Victor Caliman

*Engenheiro full-stack (TypeScript · Bun) construindo plataformas ao vivo, assistidas por IA, para narrativa colaborativa.* — 🇧🇷 Brasil · @ Deloitte

#### 🍂 Em desenvolvimento — [Arquivo Masoria](https://archive.masoria-universe.com)

Uma **plataforma full-stack ao vivo** para um universo de roleplay colaborativo — um **arquivo** público e somente-leitura de arcos narrativos, personagens e o *panteão de Ascensão*.

**No ar → [archive.masoria-universe.com](https://archive.masoria-universe.com)** &nbsp;·&nbsp; **Comunidade → [discord.gg/ansenfall](https://discord.gg/ansenfall)**

| Camada | Stack |
| --- | --- |
| **Web** | Next.js 16 · React 19 (RSC) |
| **API** | Bun · Hono · Drizzle |
| **Tempo real** | `Bun.serve` — distribuição WebSocket |
| **Bot** | Discord — proxy de personagem (*falas*) · assistente de criação · menus de cargo |
| **Motor** | Combate e crafting agnóstico de framework, só com zod |

…tudo sobre **PostgreSQL + Docker**, entregue com um fluxo **multiagente assistido por IA** (Claude Code + Codex + agent [skills](https://skills.sh)).

#### 🦖 Lançado recentemente — Primord Survival Dashboard

Painel de controle exclusivo para membros de uma comunidade self-hosted de *The Isle: Evrima* — login com Steam, operações de servidor ao vivo, armazenamento de dinossauros, mapa ao vivo, um estúdio de skins 3D e ferramentas de administração.

**No ar (exclusivo p/ membros) → [painel.primord-oficial.com](https://painel.primord-oficial.com)**

| Camada | Stack |
| --- | --- |
| **Web** | Next.js 15 · React · Three.js (Estúdio de Skins 3D) |
| **Autenticação** | Auth.js / NextAuth 5 — login com Steam, identidade via SteamID64 |
| **Serviços** | Monorepo TypeScript (pnpm) — API · daemon RCON · bot do Discord · log-tailer |
| **Integração** | Helper nativo em **C++** para controle do servidor ao vivo |
| **Infra** | PostgreSQL · Docker · Cloudflare Tunnel |

#### 🎬 duet-video-synth — trilhas, renderizadas em código

Um motor de videoclipes (dueto/solo) reativo ao áudio e guiado por configuração, sobre **[Remotion](https://www.remotion.dev)**. Todo vídeo do canal **[▶ @ansenfall](https://www.youtube.com/@ansenfall)** é renderizado com ele. *(As miniaturas estão na versão em inglês, logo abaixo.)*

#### 🛠 Trabalhos selecionados

| Projeto | O que é |
| --- | --- |
| **[RenPy-WeaponPlugin](https://github.com/sum117/RenPy-WeaponPlugin)** ⭐ | Sistema interativo de armas (disparo · recarga) para o motor de visual novels **Ren'Py** |
| **[trinity-discordx](https://github.com/sum117/trinity-discordx)** | *"Discord Roleplaying. Redefined."* — bot de RP cheio de recursos (discordx · TypeScript) |
| **[CantYouSeeImBusy](https://github.com/sum117/CantYouSeeImBusy)** | **Mod de RimWorld em C#** (no Steam Workshop) — mantém os colonos focados em combate |
| **[the-conductor](https://github.com/sum117/the-conductor)** | **Bot de música** do Discord self-hosted — Bun · yt-dlp · ffmpeg · Docker |
| **[masoria-parser](https://github.com/sum117/masoria-parser)** | O pequeno parser de visual novel onde *Masoria* começou |

**Open source — PRs aceitos:** **[oven-sh/bun](https://github.com/oven-sh/bun/pull/5513)** &nbsp;·&nbsp; **[discordx](https://github.com/discordx-ts/discordx/pull/886)** &nbsp;·&nbsp; **[botlabs-gg/yagpdb](https://github.com/botlabs-gg/yagpdb/pull/1656)**

> 🧰 **Toolbox** e 📊 **Activity** ficam logo abaixo — são universais (badges e gráficos).

</details>

---

## 🍂 Currently building — [Arquivo Masoria](https://archive.masoria-universe.com)

A **live, full-stack platform** for a collaborative roleplaying universe — a public, read-only **archive** of narrative arcs, characters, and the *panteão de Ascensão*.

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

## 🎬 duet-video-synth — soundtracks, rendered in code

A config-driven, audio-reactive **duet/solo music-video engine** built on **[Remotion](https://www.remotion.dev)**. Every track on **[▶ @ansenfall](https://www.youtube.com/@ansenfall)** is rendered with it.

<p align="center">
  <a href="https://www.youtube.com/watch?v=5T77Mh8gK-E"><img width="260" src="https://img.youtube.com/vi/5T77Mh8gK-E/maxresdefault.jpg" alt="BGM: The Solar Memories" /></a>
  <a href="https://www.youtube.com/watch?v=rJGLpBK0KIY"><img width="260" src="https://img.youtube.com/vi/rJGLpBK0KIY/maxresdefault.jpg" alt="BGM: The Red Memories" /></a>
  <a href="https://www.youtube.com/watch?v=8tv5amZ_DEo"><img width="260" src="https://img.youtube.com/vi/8tv5amZ_DEo/maxresdefault.jpg" alt="BGM: The Lunar Memories" /></a>
  <a href="https://www.youtube.com/watch?v=veX89QSSr-M"><img width="260" src="https://img.youtube.com/vi/veX89QSSr-M/maxresdefault.jpg" alt="BGM: Facing The Radiants" /></a>
  <a href="https://www.youtube.com/watch?v=JKmweAtxFeU"><img width="260" src="https://img.youtube.com/vi/JKmweAtxFeU/maxresdefault.jpg" alt="Paenitet Theme: I Only Wait" /></a>
  <a href="https://www.youtube.com/watch?v=ebCt71cUu6Q"><img width="260" src="https://img.youtube.com/vi/ebCt71cUu6Q/maxresdefault.jpg" alt="Astella Theme: The Autumn Years" /></a>
</p>

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

**Bots · Realtime · Creative**  
![discord.js](https://img.shields.io/badge/discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge)
![Remotion](https://img.shields.io/badge/Remotion-000000?style=for-the-badge&logo=remotion&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white)
![Ren'Py](https://img.shields.io/badge/Ren%27Py-663399?style=for-the-badge)

**Workflow**  
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

## 📊 Activity

<p align="center">
  <img height="165" src="https://github-readme-stats-sum117s-projects.vercel.app/api?username=sum117&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=tokyonight" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats-sum117s-projects.vercel.app/api/top-langs/?username=sum117&layout=compact&count_private=true&size_weight=0.5&count_weight=0.5&langs_count=8&hide_border=true&theme=tokyonight" alt="Top languages" />
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
