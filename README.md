<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║   葉   Phasathat "Tasachi" Jaruchitsophon  ·  藍 indigo theme  ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1b2a4a,50:2c5364,100:4a6fa5&height=200&section=header&text=%E3%81%93%E3%82%93%E3%81%AB%E3%81%A1%E3%81%AF%E3%80%81%E4%B8%96%E7%95%8C&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Phasathat%20%22Tasachi%22%20Jaruchitsophon&descAlignY=58&descSize=18" alt="header" />

<!-- ── typing tagline ─────────────────────────────────────────── -->
<a href="https://github.com/Tasachii">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=2C5364&center=true&vCenter=true&width=620&lines=Software+Engineer+%C2%B7+Backend+%C2%B7+Full-Stack;%E8%81%B7%E4%BA%BA+%E2%80%94+I+sweat+the+hard+parts;Ships+code+that+is+tested%2C+deployed%2C+documented" alt="typing" />
</a>

<br/>

<!-- ── meta badges ────────────────────────────────────────────── -->
<img src="https://komarev.com/ghpvc/?username=Tasachii&label=%E8%A8%AA%E5%95%8F%E8%80%85%20visitors&color=2c5364&style=flat-square" alt="views" />
&nbsp;
<img src="https://img.shields.io/badge/Bangkok-%E3%83%90%E3%83%B3%E3%82%B3%E3%82%AF-2c5364?style=flat-square&logo=googlemaps&logoColor=white" alt="location" />
&nbsp;
<img src="https://img.shields.io/badge/Kasetsart%20University-SE%20%2723--%2728-1b2a4a?style=flat-square&logo=googlescholar&logoColor=white" alt="university" />

</div>

---

<div align="center">

### 「 つくる 」 — I build software that actually ships.

</div>

```typescript
const tasachi = {
  role:     ["Software Engineer", "Backend Engineer", "Full-Stack Developer"],
  based_in: "Bangkok, Thailand 🇹🇭",
  study:    "3rd-yr Software Engineering @ Kasetsart University",
  craft:    "職人 — local-first apps, realtime backends, AI tooling",
  focus:    "correctness under edge cases · tested · deployed · documented",
  motto:    "終わりよければすべてよし — all's well that ends well",
};
```

<br/>

## 🛠️ 道具 — Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=ts,js,python,cpp&theme=dark" alt="languages" />
<img src="https://img.shields.io/badge/SQL-2c5364?style=for-the-badge&logo=postgresql&logoColor=white" alt="sql" />

**Backend & API**

<img src="https://skillicons.dev/icons?i=nodejs,nestjs,fastapi,docker,nginx&theme=dark" alt="backend" />
<img src="https://img.shields.io/badge/Fastify-000?style=for-the-badge&logo=fastify&logoColor=white" alt="fastify" />
<img src="https://img.shields.io/badge/WebSocket-2c5364?style=for-the-badge&logo=socketdotio&logoColor=white" alt="ws" />
<img src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="claude" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,html,css&theme=dark" alt="frontend" />
<img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" alt="pwa" />

**Databases**

<img src="https://skillicons.dev/icons?i=postgres,sqlite,mongodb&theme=dark" alt="databases" />
<img src="https://img.shields.io/badge/IndexedDB%20(Dexie)-1b2a4a?style=for-the-badge&logo=javascript&logoColor=white" alt="indexeddb" />

**Testing · Tools · Data**

<img src="https://skillicons.dev/icons?i=vitest,git,github,githubactions&theme=dark" alt="tools" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" alt="playwright" />
<img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="spark" />
<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="databricks" />

</div>

<br/>

## 📦 作品 — Featured Projects

> 「 神は細部に宿る 」 — God is in the details. Every project below is tested, deployed, and documented.

<table>
<tr>
<td width="50%" valign="top">

### 🪙 Pocketo · 家計簿
**On-device Finance PWA + Thai Tax Estimator**

A digital *kakeibo* — log a transaction in 3 taps, every byte stays on your device. No server, no account. Money is stored as integer satang and balances recompute from the log, so **zero floating-point money bugs**. Thai income-tax estimator with an SSF/RMF "save Y" simulator. Hand-rolled SVG charts (~110 KB), **89 tests** in CI.

`React 18` `TypeScript` `Vite` `Dexie` `Vitest` `Playwright`

[**→ repo**](https://github.com/Tasachii/pocketo)

</td>
<td width="50%" valign="top">

### ✅ TodoDesu · 任務
**Local-first Todo: Terminal CLI + Web, one source of truth**

CLI captures fast, GUI organizes well — so I made both *equal clients of one API*. A task added in the terminal shows on the board instantly. One Fastify REST API over a single SQLite file is the only authority; timezone-correct "today", timestamp-derived focus timer, fractional sort keys for drag-and-drop. Ships to **native iOS** via Capacitor.

`Node.js` `Fastify` `SQLite` `React` `Capacitor` `PWA`

[**→ repo**](https://github.com/Tasachii/TodoDesu)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📋 LINE Task Manager · 看板
**Realtime Kanban board wired into LINE group chats**

Thai teams plan in LINE, but tasks get buried in the scroll. This bot turns messages into Kanban cards and posts status back. Webhook verifies LINE signatures, dedupes retries, extracts tasks via **Claude API (fail-open)**. Concurrent drags can't corrupt order thanks to per-column **PostgreSQL advisory locks**. One `docker compose` up.

`TypeScript` `NestJS` `PostgreSQL` `WebSocket` `Docker`

[**→ repo**](https://github.com/Tasachii/LIne_Task_Manager)

</td>
<td width="50%" valign="top">

### 📖 Sarup Lem · 要約
**AI Book Summarizer (Thai), cost-aware**

Summarizing a whole Thai book with AI is slow and the price is unpredictable. This streams a chapter-by-chapter summary from PDF / DOCX / TXT / Markdown — counting tokens and **showing the price in Baht before any call**. Follow-up questions cost ~90% less via **prompt caching**. Exports to Markdown with local history.

`Next.js` `TypeScript` `Claude API` `Streaming` `Tailwind`

[**→ repo**](https://github.com/Tasachii/Sarup-Lem)

</td>
</tr>
</table>

<br/>

## 📊 統計 — GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Tasachii&show_icons=true&hide_border=true&title_color=2c5364&icon_color=4a6fa5&text_color=808080&bg_color=00000000&include_all_commits=true&count_private=true" alt="stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tasachii&layout=compact&hide_border=true&title_color=2c5364&text_color=808080&bg_color=00000000&langs_count=8" alt="top-langs" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Tasachii&hide_border=true&background=00000000&ring=2c5364&fire=4a6fa5&currStreakLabel=2c5364&sideLabels=808080&dates=808080&currStreakNum=2c5364&sideNums=2c5364" alt="streak" />

</div>

<br/>

## 📫 連絡 — Reach Me

<div align="center">

<a href="mailto:kazutokung59@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email" />
</a>
<a href="https://github.com/Tasachii">
  <img src="https://img.shields.io/badge/GitHub-1b2a4a?style=for-the-badge&logo=github&logoColor=white" alt="github" />
</a>
<img src="https://img.shields.io/badge/Bangkok%2C%20Thailand-2c5364?style=for-the-badge&logo=googlemaps&logoColor=white" alt="loc" />

</div>

<br/>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4a6fa5,50:2c5364,100:1b2a4a&height=120&section=footer&text=%E3%81%82%E3%82%8A%E3%81%8C%E3%81%A8%E3%81%86&fontColor=ffffff&fontSize=28&fontAlignY=70" alt="footer" />

<sub>「 一期一会 」 — treasure every encounter. Thanks for stopping by.</sub>

</div>

<!-- profile README · Tasachii -->
